
<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
import AppFooterDown from './components/AppFooterDown.vue'
import AppHero from './components/AppHero.vue'
export default {
  components : {
    AppHeader,
    AppMain ,
    AppFooter,
    AppFooterDown,
    AppHero
  }
}
 </script>

<template>
  <header>
    <AppHeader></AppHeader>
  </header>
  <main>
    <AppHero></AppHero>
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