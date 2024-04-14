
<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
import AppFooterDown from './components/AppFooterDown.vue'
export default {
  components : {
    AppHeader,
    AppMain ,
    AppFooter,
    AppFooterDown
  }
}
 </script>

<template>
  <header>
    <AppHeader></AppHeader>
  </header>
  <main>
    <AppMain></AppMain>
  </main>

  <footer>
   <AppFooter></AppFooter> 
   <AppFooterDown></AppFooterDown>
  </footer>


</template>

<style lang="scss">
@use './style/generic'
</style>