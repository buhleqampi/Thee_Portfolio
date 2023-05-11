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
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}

.content {
  background-color: #1f1f1f;
  min-width:100vh;
}
</style>