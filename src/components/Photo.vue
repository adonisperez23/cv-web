<template>
    <img class="foto" src="fotograduacion.jpg" alt="">
    <h2>{{Nombre_completo}}</h2>
    <h3>{{titulo}}</h3>
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
    height: 230px;
    max-width: 225px;
    /* margin-left: 200px; */
  }
  h3{
    margin-top: initial;
  }

</style>
