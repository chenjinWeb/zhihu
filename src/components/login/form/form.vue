<template>

  <form>

    <div class="form">

      <input type="text" placeholder="手机号码或者邮箱">

      <input type="password" placeholder="密码">

    </div>

    <button class="btn">登录</button>

    <div class="extra">

      <button class="phone-login" @click="mobileLogin($event)">手机验证码登录</button>

      <button class="link fr">无法登录?</button>

    </div>

    <div class="extra">

      <button class="link">社交账号登录</button>

    </div>

  </form>

</template>

<script>

  export default{
    name:"mainForm",
    methods:{
      mobileLogin:function (event){
        event.preventDefault()
      }
    }
  }

</script>

<style scoped>
  .form input{
    line-height: 19px;
    color: #555;
    background: #fff;
    padding: 1em .8em;
    width: 100%;
    box-sizing: border-box;
    outline: none;
    font-size: 14px;
    border: 1px solid #CCCCCC;
  }
  .form input[type=text]{
    border-bottom: none;
  }
  .btn{
    display: block;
    padding: 0;
    width: 100%;
    font-size: 15px;
    margin-top: 18px;
    color: #fff;
    text-align: center;
    text-shadow: 0 1px 1px rgba(0, 0, 0, .2);
    background: #0f88eb;
    box-shadow: none;
    border: 0;
    border-radius: 3px;
    line-height: 41px;
    cursor: pointer;
  }

  div.extra{
    margin-top: 20px;
  }

  .phone-login{
    padding: 0;
    font-size: 14px;
    color: #5ca5e8;
    background: transparent;
    border: 0;
    cursor: pointer;
    outline: 0;
  }

  button.fr{ float: right;}

  .link{
    font-size: 14px;
    color: #555;
    padding: 0;
    cursor: pointer;
    background: transparent;
    border: none;
    outline: none;
  }

</style>



