<script setup>
import NavBar from './components/NavBar.vue'
import FrontPage from './components/FrontPage.vue'
</script>

<template>

  <main>
    <NavBar/>
    <div class="background">
      <img src='./assets/Paddle.JPEG'>
    </div>
    <div>
      <h3>Hello World!</h3>
    </div>
  </main>


</template>

<style>
  .background img{
    width: 100px;
    
  }
</style>
