<script setup>

import MenuView from "@/views/MenuView.vue";
import ArtistView from "@/views/ArtistView.vue";
import ButtonDeconnexion from "@/components/ButtonDeconnexion.vue";
</script>

<template>
  Section Gauche
  <div id="menu-view">
    <MenuView ></MenuView>

    <div id="buttonDeconnexion">
      <ButtonDeconnexion></ButtonDeconnexion>
    </div>
  </div>

</template>

<style scoped>
  #buttonDeconnexion{
    position: relative;
    top: 470px;


  }
  #menu-view{
    background: #faf;
    padding: 0;
    display: flex;
    justify-content: space-around;
    flex-direction: column;


  }
</style>