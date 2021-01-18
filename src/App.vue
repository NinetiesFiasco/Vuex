<template>
  <div id='start'>
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'Start',
  data() {
    return {
      msg: "Hi here 9000"
    }
  }
}
</script>

<style scoped>
#start{
  width: 100px;
  height: 100px;
  background: red;
}
</style>