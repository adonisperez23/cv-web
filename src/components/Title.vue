<template>
  <div class="container text-center margin-y mobile-title">
    <!-- <img class="foto" loading="lazy" src="/foto-adonis.jpg" alt=""> -->
    <h2 class="margin-y">{{ Nombre_completo }}</h2>
    <h3>{{ titulo }}</h3>
  </div>
</template>

<script setup>
const Nombre_completo = 'Adonis David Pérez Farias'
const titulo = 'Desarrollador web'
</script>
<style scoped>
@media (max-width:576px) {
  .mobile-title {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: flex-start;
    align-items: center;
    align-content: flex-start;
  }
}
</style>
