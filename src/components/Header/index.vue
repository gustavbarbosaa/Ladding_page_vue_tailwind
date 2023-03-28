<template>
    <div id="header" class="flex justify-around p-8">
      <div class="flex items-center gap-2">
          <h2 class="font-bold font-roboto text-white text-2xl">Hallow<span class="text-orange-500">ee</span>nd</h2>
          <img src="../../assets/img-header.svg" alt="">
      </div>
      <nav>
          <ul class="flex items-center gap-8 font-medium text-base text-white">
              <li><a href="#">Home</a></li>
              <li><a href="#">Category</a></li>
              <li><a href="#">About</a></li>
              <li><a href="#">Trick Or Treat</a></li>
              <button class="w-36 h-14 bg-orange-500 rounded-3xl">DONATE</button>
          </ul>
      </nav>
    </div>
  </template>
  
  <script lang="ts">
  export default {
      name: 'headerComponent',
  }
  </script>