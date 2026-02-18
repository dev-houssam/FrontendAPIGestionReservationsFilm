<script setup>

import UserItem from "@/components/UserItem.vue";
</script>

<template>
  SubSubSection - Utilisateur
  <h1>Userthèque</h1>
  <div class="user-item">
    <UserItem></UserItem>
  </div>
  <div class="user-item">
    <UserItem></UserItem>
  </div>
  <div class="user-item">
    <UserItem></UserItem>
  </div>
  <div class="user-item">
    <UserItem></UserItem>
  </div>
  <div class="user-item">
    <UserItem></UserItem>
  </div>
  <div class="user-item">
    <UserItem></UserItem>
  </div>


</template>

<style scoped>
  .user-item{
    margin: 1%;
    border-bottom: 1px solid grey;
    width: 100%;
  }


</style>