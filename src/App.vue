<script setup>
import MyHello from './components/MyHello.vue'
</script>

<template>
  <div class="wrapper">
    <MyHello title="Кроссовки Puma" :price="8228" />
    <MyHello />
    <MyHello />
  </div>
</template>

<style>
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
