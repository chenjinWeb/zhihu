<template>
  <login></login>
</template>

<script>

  import login from "./components/login/index.vue"

  export default {
    name: 'app',
    components:{
      login
    }
  }
</script>

<style>

  body{
    background: #f7fafc;
  }

</style>
