<script setup>

import PaymentItem from "@/components/PaymentItem.vue";
</script>


<template>
  SubSubSection - Payement
  <h1>Payementheque</h1>
  <div>
    <div class="payment-item">
      <PaymentItem></PaymentItem>
    </div>
    <div class="payment-item">
      <PaymentItem></PaymentItem>
    </div>
    <div class="payment-item">
      <PaymentItem></PaymentItem>
    </div>
    <div class="payment-item">
      <PaymentItem></PaymentItem>
    </div>
    <div class="payment-item">
      <PaymentItem></PaymentItem>
    </div>
  </div>
</template>

<style scoped>
  .payment-item{
    border-bottom: 1px solid black;
    padding: 1%;
  }
</style>