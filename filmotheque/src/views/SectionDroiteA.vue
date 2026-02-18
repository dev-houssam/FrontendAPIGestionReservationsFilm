<script setup>

import ArtistView from "@/views/ArtistView.vue";
import MovieView from "@/views/MovieView.vue";
import UserView from "@/views/UserView.vue";
import PaymentView from "@/views/PaymentView.vue";
</script>

<template>
SubSection A
  <div id="vues-dif-sections">
    <div id="movie-view">
      <MovieView></MovieView>
    </div>

    <div id="user-view">
      <UserView></UserView>
    </div>

    <div id="artist-view">
      <ArtistView></ArtistView>
    </div>

    <div id="payement-view">
      <PaymentView></PaymentView>
    </div>


  </div>
</template>

<style scoped>
#payement-view{
  background: linear-gradient(to right, white, white, lightblue, white);

}

#artist-view{
  background: linear-gradient(to right, white, white, lightsteelblue, white);

}
#movie-view{
  background: yellow;
}
#user-view{
  background: linear-gradient(to right, white, white, lightcyan, white);
}
  #vues-dif-sections{
    background: #8fde98;
    width: 100%;
    overflow-x: scroll;
  }
</style>