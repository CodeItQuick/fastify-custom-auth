<template>
  <v-app-bar :elevation="2" rounded>
    <template v-slot:prepend>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </template>

    <template v-slot:title>
      <v-btn variant="text" to="/registration">Registration</v-btn>
      <v-btn variant="text" to="/login">Login</v-btn>
      <v-btn variant="text" @click="handleLogout">Logout</v-btn>
    </template>

    <v-app-bar-title>Application Bar</v-app-bar-title>
  </v-app-bar>
</template>

<script setup>
// import { useRouter } from 'vue-router'
//
// const router = useRouter()
//
// const handleLogout = () => {
//   // Add logout logic here (e.g., clear tokens, user data)
//   router.push('/')
// }
</script>

<style scoped lang="sass">
</style>
