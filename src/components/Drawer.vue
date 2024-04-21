<script setup>
import DrawerHead from './DrawerHead.vue'
import CardItemList from './CardItemList.vue'
</script>

<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="fixed top-0 right-0 bg-white h-full w-96 z-20 p-8">
    <DrawerHead />

    <CardItemList />

    <div class="flex flex-col gap-4 mb-6">
      <div class="flex gap-2">
        <span>Итого:</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>12999 руб.</b>
      </div>

      <div class="flex gap-2">
        <span>НДС 5%:</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>649,95 руб.</b>
      </div>
    </div>
    <button class="transition bg-lime-500 hover:bg-lime-600 active:bg-lime-700 w-full rounded-2xl py-3 text-white">Оформить заказ</button>
  </div>
</template>
