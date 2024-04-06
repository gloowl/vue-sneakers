<script setup>
defineProps({
  title: String,
  price: Number
})
</script>

<template>
  <div class="product">
    <h2>Товар: {{ title }}</h2>
    <h3>Цена: {{ price }}</h3>
  </div>
</template>

<style scoped>
.product {
  margin: 10px;
  border: 1px solid #e49a3f;
  border-radius: 7px;
  padding: 10px;
}
</style>
