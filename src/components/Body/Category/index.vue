<template>
  <div id="category" class="flex flex-col justify-center text-center">
    <h1 class="font-bold font-roboto text-6xl text-white pt-52 pb-14">Category</h1>
    <div class="flex justify-between px-60">
        <div id="card" class="flex flex-col justify-around h-96 w-60">
            <img src="../../../assets/category1-img.svg" alt="">
            <h2 class="text-white text-3xl font-semibold font-roboto">Ghost</h2>
            <p class="font-normal font-roboto text-white text-sm">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur. </p>
        </div>
        <div id="card" class="flex flex-col justify-around h-96 w-60">
            <img src="../../../assets/category2-img.svg" alt="">
            <h2 class="text-white text-3xl font-semibold font-roboto">Witch</h2>
            <p class="font-normal font-roboto text-white text-sm">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur. </p>
        </div>
        <div id="card" class="flex flex-col justify-around h-96 w-60">
            <img src="../../../assets/category3-img.svg" alt="">
            <h2 class="text-white text-3xl font-semibold font-roboto">Pumpkin</h2>
            <p class="font-normal font-roboto text-white text-sm">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur. </p>
        </div>
    </div>
  </div>
</template>

<script lang="ts">

export default {
    name: 'categoryComponent',
}
</script>