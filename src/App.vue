<template>
  <HomePage msg="hi this works" />
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>

body {
  background-image: url('./assets/bg.png');
  margin: 0;
  padding: 0;
}

</style>
