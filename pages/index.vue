<template>
  <div>
    <Navbar />
    <section class="section">
      <div class="container is-fluid">
        <h1 class="title">
          Commandes
        </h1>
        <p class="subtitle">
          Liste des commandes à exporter
        </p>
        <Orders :orders="orders" />
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Orders from '~/components/Orders.vue'

export default {
  components: {
    Navbar, Orders
  }
}
</script>
