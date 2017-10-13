<template>
  <div class="hello">
    <name></name>
  </div>
</template>

<script>
import Name from './Name'
export default {
  name: 'Vote',
  components:{Name}
}
</script>
<style >
  div{
    background-color: #70e8f7;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
</style>
