<template>
  <div>
    <div>
      <span><strong>Fecha de nacimiento:</strong> {{datos_personales.fecha_nacimiento}} </span>
      <span><strong>Cedula de Identidad:</strong> {{datos_personales.ci}}</span>
      <span><strong>Dirección:</strong> {{datos_personales.direccion}}</span>
      <span><strong>Email:</strong> {{datos_personales.email}}</span>
      <span><strong>Telefono</strong> {{datos_personales.telefono}}</span>
    </div>
  </div>
</template>

<script setup>
  const datos_personales = {
    fecha_nacimiento:'01-10-1993',
    ci:'23.917.268',
    direccion:'Av. Orinoco, frente a la Agencia Unida de Automóviles (Chevrolet), casa #304-A. Edo. Monagas',
    email:'Adonisdavid20@gmail.com',
    telefono: '0414-8942782'
  }
</script>
<style scoped>
  span{
    display: block;
  }
</style>
