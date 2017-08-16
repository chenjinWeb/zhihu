<template>

  <div class="ycmedia">
    <h1>知乎</h1>
    <p>与世界分享你的知识、经验和见解</p>
    <section>
      <slot></slot>
    </section>
    <footer>
      <button class="downloadApp">下载知乎APP</button>
    </footer>
  </div>

</template>

<script>

  export default{
    name:"layout"
  }

</script>


<style scoped>

  .ycmedia{
    width: 300px;
    height: 480px;
    position: absolute;
    top: 50%;
    left: 50%;
    margin-left: -150px;
    margin-top: -240px;
  }

  .ycmedia h1{
    font-size: 0;
    width: 160px;
    height: 74px;
    background: url("img/logo.png") no-repeat;
    margin: 0 auto;
  }

  .ycmedia p{
    font-family:'Microsoft YaHei', 'Helvetica Neue', Helvetica, 'PingFang SC', 'Hiragino Sans GB', 'Microsoft YaHei', Arial, sans-serif;
    color: #555555;
    font-size: 18px;
    font-weight: 400;
    width: 300px;
    text-align: center;
    margin: 30px 0 20px;
  }

  .downloadApp{
    margin-top: 18px;
    display: block;
    padding: 0;
    width: 100%;
    height: 41px;
    line-height: 39px;
    color: #5fa6e5;
    background: 0 0;
    border: 1px solid #96c2e9;
    border-radius: 3px;
    cursor: pointer;
    outline: 0;
    font-size: 14px;
  }

</style>



