<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>welcome to docker-jenkins-vue</div>
    <div>DJV</div>
    <div>commit must 'djv: xxx'</div>
  </div>
</template>

<script>
// import axios from 'axios'
// axios.get('/api', {
//   params: {}
// }).then((res) => {
//   console.log(res)
// })

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to DJV'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
