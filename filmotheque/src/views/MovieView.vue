<script setup>

import MovieCard from "@/components/MovieCard.vue";
</script>


<template>
  SubSubSection - Film
  <h1>Filmothèque</h1>
  <div id="movie-galery">

    <div class="pancarte">
      <MovieCard></MovieCard>
    </div>
    <div class="pancarte">
      <MovieCard></MovieCard>
    </div>
    <div class="pancarte">
      <MovieCard></MovieCard>
    </div>
    <div class="pancarte">
      <MovieCard></MovieCard>
    </div>
  </div>

</template>

<style scoped>
  .pancarte{
    margin: 1%;
    width: 150px;
    border: 1px solid black;
    border-radius: 5px;
  }
  #movie-galery{
    display: flex;
    padding: 1%;
    background: linear-gradient(to right, whitesmoke, white, mediumaquamarine, lightsteelblue, navajowhite, whitesmoke);
  }
</style>