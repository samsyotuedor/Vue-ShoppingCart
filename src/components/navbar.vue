<template>
  <div id="nav">
     <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/login">Login</router-link> |
      <router-link to="/signup">SignUp</router-link>
  </div>
</template>

<script>
export default {
  name: 'nav'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#nav{
    background-color: dimgrey;
    color: whitesmoke;
}
</style>
