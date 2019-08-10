<template>
  <div class="app">
   
    <cmp-nav></cmp-nav>
<router-view/>
  </div>
</template>

<script>
import nav from "./Components/NavBar"
export default {
components:{
  cmpNav:nav
}
}
</script>

<style lang="scss" scoped>


</style>