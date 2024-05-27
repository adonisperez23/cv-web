<script setup>
import AcademicFormation from './components/AcademicFormation.vue'
import Courses from './components/Courses.vue'
import Experience from './components/Experience.vue'
import Photo from './components/Photo.vue'
import Skills from './components/Skills.vue'
// import Aboutme from './components/Aboutme.vue'
import Contact from './components/Contact.vue'

function downloadPdf() {
  window.print()
}

</script>

<template>
  <div class="inter">
    <div class="container total-width">
      <div class="box">
        <Photo />
      </div>
      <hr>
      <Contact />
      <hr>
    </div>
    <div class="container total-width">
      <!-- <Aboutme /> -->
      <Experience />
      <hr>
      <AcademicFormation />
      <hr>
      <Courses />
      <hr>
      <Skills />
      <hr>
      <div class="text-center margin-y">
        <button @click="downloadPdf">Descargar PDF <i class="bi bi-download"></i></button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.total-width {
  width: 1024px;
}
</style>
