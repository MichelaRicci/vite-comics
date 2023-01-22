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

<style lang="scss">
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

h4,
h3 {
  text-transform: uppercase;
}


/* Row & Cols */

.row {
  display: flex;
  align-items: center;



}

.col {
  width: 50%;
  display: flex;

  align-self: center;

  margin-left: 15px;

}
</style>
