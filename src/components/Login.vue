<template>
  <div>
    <!--<form method="get" action="http://localhost:8080/ssm/user/insert">-->
    <form @submit.prevent="submit">
      <table>
        <tr>
          <td><h1>{{username}}</h1></td>
        </tr>
        <tr>
          <td><h1>{{password}}</h1></td>
        </tr>
        <tr>
          <td>username:</td>
          <td><input v-model="username" type="text" name="username"/></td>
        </tr>
        <tr>
          <td>password:</td>
          <td><input v-model="password" type="password" name="password"/></td>
        </tr>
      </table>
      <input type="submit" value="提交">
    </form>
  </div>
</template>

<script>
  export default {
    name: 'Login',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App',
        username: 'username',
        password: 'password'
      }
    },
    methods: {
      submit: function () {
        console.log("submit");
        console.log("username = " + this.username);
        console.log("password = " + this.password);
      }
    }
  }
</script>

<style scoped>

</style>
