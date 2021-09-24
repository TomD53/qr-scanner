<template>
  <nav class="level is-mobile">
    <div class="level-item">
      <h1 class="subtitle">by Pete and Tom</h1>
    </div>
    <div class="level-item">
      <div class="buttons">
        <router-link to="/" class="button">Home</router-link>
        <router-link to="/about" class="button">About</router-link>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Nav"
}
</script>