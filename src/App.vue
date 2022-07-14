<template>
  <div id="app">
     <div>
      <heroImg/>
      <div>
        <headerTitle/>
      </div>
    </div>
  </div>
</template>

<script>
import headerTitle from './components/headerTitle.vue'
import heroImg from './components/hero.vue'

export default {
  name: 'App',
  components: {
    headerTitle,
    heroImg
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>