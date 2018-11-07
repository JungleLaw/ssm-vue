<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--<router-view/>-->
    <!--<div>
      <tr>
        <td>username:</td>
        <td><input type="text"/></td>
      </tr>
      <tr>
        <td>password:</td>
        <td><input type="text"/></td>
      </tr>
    </div>-->
    <Login></Login>
  </div>

</template>

<script>
  /*export default {
    name: 'App'
  }*/
  // import Hello from './components/HelloWorld'
  //
  // export default {
  //   components: {
  //     Hello
  //   }
  // }
  import Login from './components/Login'

  export default {
    components: {
      Login
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
