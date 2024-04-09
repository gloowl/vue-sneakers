<script setup>
defineProps({
  title: String,
  imageUrl: String,
})
</script>

<template>
  <div
    class="relative bg-white border border-slate-100 rounded-3xl p-8 cursor-pointer transition hover:-translate-y-2 hover:shadow-xl"
  >
    <img src="/like-1.svg" alt="Like-1" class="absolute top-8 left-8" />
    <img :src="imageUrl" alt="Sneaker" />

    <p class="mt-5">{{ title }}</p>

    <div class="flex justify-between mt-5">
      <div class="flex flex-col">
        <span class="text-slate-400">Цена:</span>
        <b>1205 руб.</b>
      </div>

      <img src="/plus.svg" alt="Plus" />
    </div>
  </div>
</template>
