<template>
  <span>
    <background></background>
    <layout>
        <main-form></main-form>
    </layout>
  </span>
</template>


<script>
  import background from "./background/background.vue"
  import layout from "./layout/layout.vue"
  import mainForm from "./form/form.vue"

  export default{
    name:"login",
    components:{
      background,
      layout,
      mainForm
    }
  }


</script>


<style scoped>



</style>
