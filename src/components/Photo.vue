<template>
  <div class="container text-center">
    <img class="foto rounded" src="/fotograduacion.jpg" alt="">
    <h2>{{Nombre_completo}}</h2>
    <h3>{{titulo}}</h3>
  </div>
</template>

<script setup>
  const Nombre_completo = 'Adonis David Pérez Farias'
  const titulo = 'Síntesis Curricular'
</script>
<style scoped>
  /* .linea{
    height: 5px;
    width: 100%;
    background-color: black;
  } */

  .foto{
    height: 150px;
    max-width: 225px;
    margin-top: 20px;
  }
  h3{
    margin-top: initial;
  }

</style>
