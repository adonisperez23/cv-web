<template>
  <div class="margin-y mobile-skills">
    <h4>Conocimientos y Habilidades</h4>
    <ul>
      <li>Manejo de Microsoft Word, Excel, PowerPoint </li>
    </ul>
    <ul>
      <li>HTML, CSS y JS</li>
    </ul>
    <ul>
      <li>Desarrollo de interfaces de usuario con Vue.js Framework</li>
    </ul>
    <ul>
      <li>Manejo de distribuciones de sistemas operativos tipo linux como Debian y Ubuntu</li>
    </ul>
    <ul>
      <li>Manejo de servicios de computacion en la nube con Digital Ocean y Amazon Web Services</li>
    </ul>
  </div>
</template>

<script setup>

</script>
<style scoped>
@media (max-width:576px) {
  .mobile-skills {
    display: flex;
    flex-direction: column;
    align-content: flex-start;
    justify-content: start;
    max-width: 350px;
  }
}
</style>
