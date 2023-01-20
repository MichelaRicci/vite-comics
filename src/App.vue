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

  font-family: sans-serif;
}

/* Generics */

.container {
  width: 1200px;
  margin: 0 auto;
}

li {
  list-style-type: none;
}

a {
  display: inline-block;
  color: #5d5d5d;
}
</style>
