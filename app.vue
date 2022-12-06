<template>

  <div>
    <NuxtLayout />
    <NuxtPage />
  </div>  
  <!-- <a @click="view('home')">Home</a>
  <a @click="view('counter')">Counter</a>
  
  <LazyHomeWelcome v-if="page === 'home'" />
  <LazyCounter v-if="page === 'counter'" /> -->
</template>

<script setup>
import './assets/css/tailwind.css'

const page = ref("home");
function view(name) {
  page.value = name;
}

</script>