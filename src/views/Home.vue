<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div class="button-block">
  <h3 v-if="$auth.isAuthenticated" class="is-size-3 has-background-dark welcome">Welcome, {{ $auth.user.name }}!</h3>
</div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
   
  }
}
</script>
<style scoped>
h3{
  color:white;
}
</style>
