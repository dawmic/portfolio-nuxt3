<template>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/skills">Skills</NuxtLink></li>
          <li><NuxtLink to="/work">Work</NuxtLink></li>
          <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <main>
      <NuxtPage />
    </main>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
  .router-link-exact-active{
      color: green;
      font-size: 2rem;
      border: 2px solid black;
      padding: 1rem;
  }
 
  
  </style>
  