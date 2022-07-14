<template>
  <div class="hero-title">
    <h1>La mia prima app con Vue CLI!</h1>
  </div>
</template>

<script>
export default {
  name: 'headerTitle',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.hero-title{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50% , -50%);
}
.hero-title h1{
  font-size: 100px;
  color: white;
  text-shadow: 5px 5px 10px red;
}
</style>
