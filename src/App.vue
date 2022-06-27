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

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;500;600&display=swap');

body {
  background-image: url('./assets/bg.png');
  margin: 0;
  padding: 0;
  font-family: 'Open'
}

</style>
