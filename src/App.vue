<template>
  <img class="logo" alt="Space Castle" src="./assets/SC-Logo.png" />
  <SpaceCastle />
</template>

<script setup>
import SpaceCastle from './components/SpaceCastle.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
</script>

<style>
html {
    height: 100%;
    width: 100%;
}
body {
    margin: 0;
    padding: 0;
    min-height: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eee;
  background-image: url('./assets/BG.jpg');
  background-position: top left;
  background-repeat: no-repeat;
  padding-bottom: 1rem;
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
}

@media only screen and (max-width: 900px) {
    #app {
        background-size: cover;
        position: relative;
    }
}

#app img.logo {
    margin-top: 5rem;
    height: 25rem;
}

#app h4 {
    width: 50%;
    margin: 2rem auto;
}
</style>
