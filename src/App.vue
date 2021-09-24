<template>
  <section class="section has-text-centered">
    <div class="container box has-text-centered">
      <router-view />
      
      <hr>
      <Nav />
    </div>
  </section>
</template>

<script>
import Nav from "@/components/Nav.vue"

export default {
  components: {
    Nav
  }
}
</script>