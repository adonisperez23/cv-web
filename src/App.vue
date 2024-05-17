<script setup>
import AcademicFormation from './components/AcademicFormation.vue'
import Courses from './components/Courses.vue'
import Experience from './components/Experience.vue'
import Photo from './components/Photo.vue'
import Skills from './components/Skills.vue'
// import Aboutme from './components/Aboutme.vue'
import Contact from './components/Contact.vue'
</script>

<template>
  <div class="color tipoletra white">
    <div class="box">
      <Photo />
    </div>
    <hr>
    <Contact />
    <hr>
  </div>
  <div class="container tipoletra">
    <!-- <Aboutme /> -->
    <hr>
    <AcademicFormation />
    <hr>
    <Experience />
    <hr>
    <Courses />
    <hr>
    <Skills />
  </div>
</template>

<style scoped></style>
