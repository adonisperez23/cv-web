<script setup>
import AcademicFormation from './components/AcademicFormation.vue'
import Courses from './components/Courses.vue'
import Experience from './components/Experience.vue'
import Photo from './components/Photo.vue'
import Skills from './components/Skills.vue'
import Title from './components/Title.vue'
import Contact from './components/Contact.vue'
</script>

<template>
  <div class="color tipoletra">
    <div class="box">
      <Photo/>
    </div>
    <hr>
    <Contact/>
    <hr>
  </div>
    <Title/>
    <hr>
    <AcademicFormation/>
    <hr>
    <Experience/>
    <hr>
    <Courses/>
    <Skills/>
</template>

<style scoped>

</style>
