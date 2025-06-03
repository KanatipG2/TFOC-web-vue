<script setup>
import { ref } from 'vue';

// For the menu, we'll use a reactive state to toggle its visibility
const showMenu = ref(false);

const toggleMenu = () => {
  showMenu.value = !showMenu.value;
};
</script>

<template>
  <nav>
    <input type="checkbox" id="show-menu" role="button" :checked="showMenu" @change="toggleMenu">
    <label for="show-menu" class="open"><span class="fa fa-bars"></span></label>
    <label for="show-menu" class="close"><span class="fa fa-times"></span></label>
    <ul id="menu" :style="{ display: showMenu ? 'initial' : 'none' }">
      <li><a class="active" href="./index.html">Main Page</a></li>
      <li><a href="./pages/types.html">About Types</a></li>
      <li><a href="./pages/categories.html">About Categories</a></li>
      <li><a href="./pages/kuyadmin.html">About Us</a></li>
      <li><a href="#">Empty</a></li>
      <li><a href="#">Also Empty</a></li>
    </ul>
  </nav>
  <div id="banner">
    <div id="header">
      <h1>TFOC Network - Boss Packs</h1>
      <p class="sub">混沌とした世界を支配する ~ Rules the world with chaos.</p>
    </div>
  </div>
  </template>

<style scoped>
</style>