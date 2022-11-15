<template>
<v-app>
  <div>
    <NuxtLink class="ma-2" to="/">Home</NuxtLink>
    <NuxtLink class="ma-2" to="/login">Login</NuxtLink>
    <NuxtLink class="ma-2" to="/reset">reset</NuxtLink>
  </div>

<Nuxt />

  <div>
    Footer
  </div>



</v-app>
</template>

<script>
export default {
  name: "home"
}
</script>

<style scoped>

</style>
