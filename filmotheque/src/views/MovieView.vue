<script setup>

import MovieCard from "@/components/MovieCard.vue";
</script>


<template>
  SubSubSection - Film
  <h1>Filmothèque</h1>
  Nombre de films : {{ nbMovies }}

  <div v-for="movie in movies" :key="movie.id" id="movie-galery">
    <div class="pancarte">
      <h3>{{ movie.titre }} {{ movie.genre }}</h3>
      <p>Voir Detail</p>
    </div>
    <p>
      <!--<button @click="cherchezDetails(movie.id, $event)">Voir details du film</button>-->
    </p>
  </div>


  <div id="movie-galery">

    <div class="pancarte">
      <MovieCard :message="baba"></MovieCard>
    </div>
    <div class="pancarte">
      <MovieCard></MovieCard>
    </div>
    <div class="pancarte">
      <MovieCard ></MovieCard>
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

<script>

export default {
  data() {
    return {
      message: "youhouuuuuuuu",
      movies: []
    }
  },
  methods : {
    cherchezDetails(id, event) {
      console.log("Details");
    },
  },
  created()  {
    fetch('http://localhost:12100/api/movies')
        .then((response) => response.json())
        .then((json) => {this.movies = json; console.log(this.movies)});
  },
  computed: {
    nbMovies() {
      return this.movies.length
    }
  },
  components:{
    MovieCard,
  }
}

</script>