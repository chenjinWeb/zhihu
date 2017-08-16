<template>

  <div class="background"></div>

</template>

<script>

  import Particle from 'zhihu-particle'

  export default{
    name:"background",
    mounted(){
      new Particle(this.$el,{interactive:true,density:"low"});
    }
  }

</script>

<style scoped>
  .background {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 0;
    overflow: hidden;
  }
</style>



