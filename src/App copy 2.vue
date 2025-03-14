<script setup>
import AlertComponenr from './components/AlertComponenr.vue';
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <div class="wrapper">
      <AlertComponenr type="success" msg="hello world"/>
      
      <AlertComponenr type="error" msg="hi there"/>

      
      <AlertComponenr type="warning" msg="Welcome back"/>
      </div>

     
    
  </header>
  
  <main>
    
  </main>
</template>

<style scoped>

</style>
