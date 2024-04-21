<script setup>
import SneakerCard from './SneakerCard.vue'

const onClickAdd = () => {
  alert("test")
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <SneakerCard
      title="Мужские кроссовки Nike Blazer Mid Suede"
      imageUrl="/sneakers/sneakers-1.jpg"
      :price="12500"
      :is-added="false"
      :is-favorite="false"
      :onClickAdd="onClickAdd"
    />
  </div>
</template>
