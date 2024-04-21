<script setup>
import MainHeader from './components/MainHeader.vue'
import CardList from './components/CardList.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
  <Drawer />

  <div class="bg-white w-4/5 m-auto rounded-xl shadow-2xl mt-14">
    <MainHeader />

    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>

      <CardList />
    </div>
  </div>
</template>
