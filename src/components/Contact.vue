<template>
  <div class="cont mobile-contact">
    <div class="">
      <i class="bi bi-geo-alt">
        Monagas, Venezuela</i>
    </div>
    <div class="">
      <i class="bi bi-linkedin"> </i> <a href="https://www.linkedin.com/in/adonisperez93/"
        target="_blank">adonisperez93</a>
    </div>
    <div class="">
      <i class="bi bi-whatsapp"> <a href="https://api.whatsapp.com/send?phone=584148942782" target="_blank">
          +584148942782
        </a> </i>
    </div>
    <div class="">
      <i class="bi bi-envelope-at"><a href="mailto:adonisdavid20@gmail.com"
          style="margin-left: 5px;">adonisdavid20@gmail.com</a>
      </i>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.cont {
  display: flex;
  justify-content: space-between;
}

i {
  margin-right: 2px;
}

@media (max-width:576px) {
  .mobile-contact {
    display: flex;
    flex-direction: column;
    align-content: flex-start;
    max-width: 576px;
  }
}
</style>
