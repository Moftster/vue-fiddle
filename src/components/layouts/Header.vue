<template>
  <header>
      <h1>New To Do</h1>
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/mytodos">My Todos</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/contact">Contact</router-link> |
        <router-link to="/login">Login</router-link>

    </div>

    </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>

</style>