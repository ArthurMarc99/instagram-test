<script setup>
import LoginForm from './components/LoginForm.vue';
import VueFooter from './components/VueFooter.vue';
</script>
<template>
  <!-- <div class="justify-center flex">
    
    <div>
      <VueFooter />
    </div>
  </div> -->
  <div class="flex flex-col h-screen justify-between">
    <div class="flex flex-col h-screen justify-center items-center">
      <LoginForm/>
    </div>
    <VueFooter/>
  </div>
  
</template>