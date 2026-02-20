<script setup>

</script>

<template>
  <span class="style_user">
    👤 - UserItem - John Huan Dwo
      <button @click="getInfoUser">Show User Details</button>

  </span>
</template>

<style scoped>
  .style_user{
    width: 100%;
    font-family: "Arial Black";
    font-size: 18px;
  }
  .style_user:hover{

    font-family: "Arial Black";
    font-size: 18px;
    background: lightgoldenrodyellow;
  }
</style>




<script>


export default {

  methods: {
    created() {
      // GET request using fetch with set headers
      const headers = { "Content-Type": "application/json" };
      fetch("http://localhost:12104/user/5", { headers })
          .then(response => response.json())
          .then(data => (this.username = data.name));
    }
  }
}
</script>