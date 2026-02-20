<script setup>
import { RouterView } from 'vue-router'
import ArtistView from "@/views/ArtistView.vue";
import Menu from "@/components/Menu.vue";
import MenuView from "@/views/MenuView.vue";
import GaucheView from "@/views/GaucheView.vue";
import DroiteView from "@/views/DroiteView.vue";
</script>

<template>
  Mode Dev.
  <div id="window">
    <div class="section-gauche"><GaucheView ></GaucheView></div>
    <div class="section-droite"><DroiteView></DroiteView></div>

  </div>
</template>

<style scoped>
  #window {
    display: flex;
    height: 950px;
  }
*{
  border: solid 1px black;
}
GaucheView{
  background: #e10f50;
}

  .section-gauche {
    width: 20%;
    //min-height: 800px;
    padding: 15px;
    background: yellow;
  }

.section-droite {
  width: 80%;
  padding: 15px;
  background: lightcyan;
}


.layout {
  width: 95% ;
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
  padding: 0px 0px;


  background: #DBD14A;
  background: linear-gradient(315deg, #726d2e, #581b9c);
}
</style>
