<script setup>
import LogoComponent from './LogoComponent.vue';
</script>
<template>
   <header class="p-4 pb-20">
    <div class="w-full max-w-7xl mx-auto">
      <div class="flex justify-between gap-8 items-center">
        <LogoComponent part1="Brand" part2="Name"/>
        <div class="flex items-center gap-8">
          <nav class="hidden lg:flex gap-8">
            <a href="" class="hover:underline">Collections</a>
            <a href="" class="hover:underline">Featured products</a>
            <a href="" class="hover:underline">Contact us</a>
          </nav>
          <span class="hidden lg:block">|</span>
          <div class="flex gap-4 text items-center">
            <a href="">
              <i
                class="flex items-center justify-center bg-black text-white rounded-full w-[35px] h-[35px] bi bi-search"></i>
            </a>
            <a href="">
              <i
                class="flex items-center justify-center bg-black text-white rounded-full w-[35px] h-[35px] bi bi-bag"></i>
            </a>
            <a href="" class="text-2xl">
              <i
                class="flex items-center justify-center bg-black text-white rounded-full w-[35px] h-[35px] bi bi-person"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>
<style scoped>
</style>