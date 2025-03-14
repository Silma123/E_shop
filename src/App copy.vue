<script setup>
import {ref} from 'vue';
 const country='Bangladesh';
 function greet(){
    alert("hello world");
 }
 const count =ref(0);
 const increment=()=>{
    count.value++;
 }
 const time="morning";
 const countries=ref([
  {name:'bangladesh',capital:'Dhaka'},
  {name:'Egypt',capital:"ciaro"},
  {name:'Australia',capital:"Sydney"},
  {name:'America',capital:'New York'}

 ]);
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <div class="wrapper">
    <h1>Welcom to our {{ country }}</h1>
    <p>The number is {{ count }}</p>
    <button @click="increment">kichu bolba</button>
    <h1 v-if="time=='morning'">Good Morning</h1>
    <h1 v-else-if="time=='afternoon'">Good afternoon</h1>
    <h1 v-else>Good evening</h1>

    <h1>Countries with capital</h1>
    <ul>
      <li v-for="country in countries":key="country.name" >
         {{ country.name }}-{{ country.capital }}
      </li>
    </ul>
   </div>

    
  </header>
  
  <main>
    
  </main>
</template>

<style scoped>

</style>
