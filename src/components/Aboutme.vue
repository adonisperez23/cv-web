<template>
  <div class="mobile-about">
    <h4 class="font-title">Perfil profesional</h4>
    <p>
      Ingeniero de sistemas con habilidades en desarrollo web. A traves de mi formación como ingeniero de sistemas me ha
      permitido llevar a cabo soluciones a empresas que han requerido encontrar alternativas eficientes cuando han
      requerido optimizar su flujo de trabajo mediante tecnologia web. Estoy en la capacidad de poder desempeñar roles
      como desarrollador
      frontend utilizando el framework Vue js y como desarrollador backend usando Node js.
    </p>
  </div>
</template>

<script setup>
const datos_personales = {
  fecha_nacimiento: '01-10-1993',
  ci: '23.917.268',
}
</script>
<style scoped>
span {
  display: block;
}

@media (max-width:576px) {
  .mobile-about {
    display: flex;
    flex-direction: column;
    align-content: flex-start;
    justify-content: start;
    max-width: 350px;
  }
}
</style>
