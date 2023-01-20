<script>

import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  data() {
    return {

    }
  },

  components: { AppHeader, AppMain, AppFooter }
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
  </footer>

</template>

<style>
/* Reset */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Generics */

.container {
  width: 1200px;
  margin: 0 auto;
}
</style>
