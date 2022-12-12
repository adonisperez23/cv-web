<script setup>
import AcademicFormation from './components/AcademicFormation.vue'
import Courses from './components/Courses.vue'
import Experience from './components/Experience.vue'
import Photo from './components/Photo.vue'
import Skills from './components/Skills.vue'
import Title from './components/Title.vue'
</script>

<template>
  <div>
    <div class="container">
      <Photo/>
    </div>
    <hr>
    
    <Title/>
    <hr>
    <AcademicFormation/>
    <hr>
    <Experience/>
    <hr>
    <Courses/>
    <Skills/>
  </div>
</template>

<style scoped>

</style>
