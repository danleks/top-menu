<template>
  <div id="app">
      <app-menu></app-menu>
  </div>
</template>

<script>
import Menu from './components/Menu.vue';

export default {
  name: 'app',
  components: {
    'app-menu': Menu
  }
}
</script>

<style lang="scss">
  html {
        box-sizing: border-box;

  }
  *, *:before, *:after {
      box-sizing: inherit;
      padding: 0;
      margin: 0;
  }

  body {
      height: 100vh;
      background-image: linear-gradient(to bottom right, purple, blue);
      background-repeat: no-repeat;
  }

  #app {
    max-width: 1000px;
    margin: 0 auto;
  }
</style>
