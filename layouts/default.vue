<template>
  <div>
    <h1>{{name}}</h1>
    <nuxt />
  </div>
</template>
<script>
export default {
  name: 'App',
  data(){
    return {
      name: "henq222"
    }
  }
}
</script>
<style lang="less">
.size{
  width: 100%;
  height: 100%;
}
html,body{
  .size;
  overflow: hidden;
  margin: 0;
  padding: 0;
}
#app {
  .size;
}
</style>
