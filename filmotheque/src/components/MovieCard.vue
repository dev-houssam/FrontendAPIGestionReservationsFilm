<script setup>

</script>

<template>

  <div id="movie-item-poster">
    <img class="img-movie-brand" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%2Fid%2FOIP.o02RtW8t20uyAycnOt_7jAHaH6%3Fpid%3DApi&f=1&ipt=53d8a84b5721acb6e9b315932e1d63d4ebf00d46133510e340f1f75c8a5d2174&ipo=images" alt="">
    <br>
    MovieCard - Film de Grade Le Schtoum - 2059 | Reponse:  {{ message }}
  </div>

</template>

<style scoped>
  .img-movie-brand{
    width: 150px;
  }
  #movie-item-title-poster{
    background: ghostwhite;
  }
</style>

<script>
  export default {
    name: "Enfantssssssss",
    data(){
      return {
        message: "hahahaha"
      }
    },
    props:{
      message: String
    }
  }
</script>