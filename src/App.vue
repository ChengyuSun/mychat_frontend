<template>
  <div id="app">
    <h1>scy chat</h1><br><br><br><br>
    <form>
      账户：<input type="text" name="account" v-model="ac"><br><br>
      密码：<input type="password" name="password" v-model="pw"><br><br><br><br>
      <button name="upload" type="button" @click="login">登录</button>
    </form>
  </div>
</template>

<script>
export default{
  data () {
    return {
      ac: '',
      pw: ''
    }
  },
  methods: {
    login: function () {
      document.write('<p>{{this.ac}}</p>')
    }
  }
}
</script>

<style scoped>
div{

    background-color: bisque;
    height: 700px;
  }
h1{
  margin: 0px;
  text-align: center;
  font-family:Calibri;
    font-size: 100px;
    color: coral;
}
  form{
    text-align: center;
    color: black;
    font-size:20px;
  }
button{
  background-color: green;
  padding: 15px 30px;
  color: white;
  font-size: 20px;

}
</style>
