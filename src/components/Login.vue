<template>
  <div id="login">
    <form action="loginCheck" method="post">
      <div class="app-input-container">
        <span class="fa fa-user"></span>
        <input id="username" name="username" class="app-input" type="text">
      </div>
      <div class="app-input-container">
        <span class="fa fa-lock"></span>
        <input id="password" name="password" class="app-input" type="password">
      </div>
      <input class="login-button" type="submit" value="登录"/>
    </form>
  </div>
</template>

<script>
export default {
  name: 'Login'
}
</script>

<style lang="scss" scoped>
#login{
  background-color: #ffffff;
  width: 300px;
  padding: 25px;
  margin: 150px auto;
  border: 2px none rgba(200,200,200,1);
  box-shadow: 0 0 8px rgba(0,0,0,0.05);
  border-radius: 8px;
  .app-input-container{
    position: relative;
  }
  .app-input{
    margin: 0 auto 35px auto;
    width: 264px;
    height: 33px;
    padding-left: 34px;
    border: 1px solid #ddd;
    font-size: 14px;
    font-family: "Microsoft YaHei UI",Arial,sans-serif;
    transition: border-color .3s ease 0s;
    outline: 0;
  }
  .login-button{
    width: 100%;
    height: 40px;
    line-height: 40px;
    color: #fff;
    cursor: pointer;
    display: block;
    font-size: 18px;
    letter-spacing: 2px;
    font-family: "Microsoft YaHei UI",Arial,sans-serif;
    text-align: center;
    border: none;
    background: #707770;
    border-radius: 2px;
  }
  span{
    position: absolute;
    font-size: 25px;
    color: #707770;
    top: 6px;
    left: 10px;
  }
}
</style>
