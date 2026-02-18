<script setup>

import AddMovieForm from "@/components/AddMovieForm.vue";
</script>

<template>
  SubSection B
  <h1>Section Détails, Ajout, Suppression, Modification</h1>
  <hr>
  <br>
  Management Forms Components
  <div id="diff-forms-section">
    <div class="forms-addMovie">
      <AddMovieForm></AddMovieForm>
    </div>
    <hr>
    <div class="forms-addMovie">
      <AddMovieForm></AddMovieForm>
    </div>
    <hr>
    <div class="forms-addMovie">
      <AddMovieForm></AddMovieForm>
    </div>
    <hr>
    <div class="forms-addMovie">
      <AddMovieForm></AddMovieForm>
    </div>
  </div>
</template>

<style scoped>
  .forms-addMovie{
    background: white;
  }
</style>