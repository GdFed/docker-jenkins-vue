<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>welcome to docker-jenkins-vue</div>
    <div>DJV</div>
    <div>commit must 'djv: 发邮件'</div>
    <div>must push master</div>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to DJV'
    }
  }
}
</script>
<style scoped>
</style>
