<template>
<NavbarComp/>
<router-view/>
<FooterComp/>
</template>

<script>
import NavbarComp from '@/components/NavbarComp.vue'
import FooterComp from '@/components/FooterComp.vue'
  export default {
    components: {
      NavbarComp, FooterComp
    }
  }
</script>
<style>
#app {
  font-family: Old Standard TT;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.content {
  background-color: #E4DBCF;
  min-height:100%;
}
</style>