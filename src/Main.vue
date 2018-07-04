<template>
  <div id="main">
    <img src="./assets/img/works.png">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'main',
  data () {
    return {
      msg: 'It works'
    }
  }
}
</script>

<style>
#main {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1{
  font-weight: normal;
}
</style>
