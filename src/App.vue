<script setup>
import AcademicFormation from './components/AcademicFormation.vue'
import Courses from './components/Courses.vue'
import Experience from './components/Experience.vue'
import Title from './components/Title.vue'
import Skills from './components/Skills.vue'
import Aboutme from './components/Aboutme.vue'
import Contact from './components/Contact.vue'

function downloadPdf() {
  window.print()
}

</script>

<template>
  <div class="inter mobile-app">
    <div class="container total-width width-mobile">
      <div class="box">
        <Title />
      </div>
      <hr>
      <Contact />
      <hr>
    </div>
    <div class="container total-width width-mobile">
      <Aboutme />
      <Experience />
      <hr>
      <AcademicFormation />
      <hr>
      <Courses />
      <hr>
      <Skills />
      <hr>
      <div class="text-center margin-y download-btn ">
        <button @click="downloadPdf">Descargar PDF <i class="bi bi-download"></i></button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.total-width {
  width: 1024px;
}

@media (max-width:576px) {
  .mobile-app {
    display: block;
    max-width: 350px;
    margin-left: 16px;
    margin-right: 16px;
    width: 375px;
  }

  hr {
    max-width: 350px;
  }

  .download-btn {
    display: flex;
    max-width: 350px;
    flex-direction: column;
  }

  .width-mobile {
    width: 375px;
  }


}
</style>
