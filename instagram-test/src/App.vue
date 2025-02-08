<script setup>
import LoginForm from './components/LoginForm.vue';
import VueFooter from './components/VueFooter.vue';
import SignUpButton from './components/SignUpButton.vue';
import GetApp from './components/GetApp.vue';
import HomePage from './components/HomePage.vue';
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <div class="flex flex-grow justify-center items-center mt-12 w-full">
      <div class="flex w-full flex-wrap justify-center">
        <div class="w-full lg:w-1/2 p-4">
          <div>
            <HomePage />
          </div>
        </div>
        <div class="w-auto lg:w-1/2 p-4 justify-center flex">
          <div class="items-center m-auto">
              <LoginForm />
              <SignUpButton/>
              <GetApp />
          </div>
        </div>
      </div>
    </div>

    <footer class="mt-auto">
      <VueFooter />
    </footer>
  </div>
</template>



