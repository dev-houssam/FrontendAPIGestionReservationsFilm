<script setup>

import ArtistView from "@/views/ArtistView.vue";
import SectionDroiteA from "@/views/SectionDroiteA.vue";
import SectionDroiteB from "@/views/SectionDroiteB.vue";
</script>

<template>
  Section Droite

  <div id="main-section">
    <div id="section-d-a">
      <SectionDroiteA></SectionDroiteA>
    </div>

    <div id="section-d-b">
      <SectionDroiteB></SectionDroiteB>
    </div>
  </div>

</template>

<style scoped>
#main-section{
  display: flex;
  width: 100%;
  height: 100%;
  border: 1px solid grey;
  //overflow-x: scroll;
}
  #section-d-a{
    background: lemonchiffon;
    width: 70%;
    overflow-x: scroll;
  }

  #section-d-b{
    background: lavender;
    width: 30%;
    overflow-x: scroll;
  }
</style>