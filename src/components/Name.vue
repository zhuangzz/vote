<template>
  <div>
    你是<input type="text" v-model='text' placeholder='你的名字'/>
  <button @click='handleClick'>提交</button>
  </div>
</template>
<script>
  export default{
    name:'name',
    data:()=>({
      text:''
    }),
    methods:{
      handleClick:function(){
        console.log(this.text)
        this.text=''
      }
    }
  }
</script>
<style scoped>
  div{
    display: flex;
    width: 200%;
    margin-top: 80px;
    flex-direction: row;
    background-color: #fff;
    margin-bottom: 110px;
    height: 85px;
    box-shadow: 0px 0px 10px #888888;
  }
  input{
   outline: none;
   border: none;
   border-bottom: 1px solid #70e8f7;
   padding-left: 10px;
   font-size: 15px;
   /*background-color: #fff;*/
 }
</style>
