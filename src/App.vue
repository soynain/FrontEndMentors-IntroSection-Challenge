<script setup>
import NavBarComponent from './components/NavBarComponent.vue';
import LeftHomePageComponent from './components/LeftHomePageComponent.vue';
import RightHomePageComponent from './components/RightHomePageComponent.vue';
</script>

<template>
  <header>
    <NavBarComponent/>
  </header>

  <main class="home-page">
    <LeftHomePageComponent/>
    <RightHomePageComponent/>
  </main>
</template>

<style scoped>
@import './assets/style.css';
.home-page{
  display:flex;
  flex-wrap: wrap;
  flex-direction: row;
  align-content: center;
  justify-content: center;
  min-height: 90.2vh;
  background-color: hsl(0, 0%, 98%);
  padding: 10px;
}

</style>
