<template>
  <div id="container-form" class="ml-52 mr-56 rounded-md">
    <div id="form" class="flex justify-around">
        <div class="text-form flex flex-col justify-center">
            <h2 class="font-noto font-bold text-6xl text-white">Subcribe</h2>
            <p class="font-roboto font-normal text-xl text-white">Subcribe to our newsletters and stay update!</p>
            <div class="input">
                <input type="email" name="email" id="email" placeholder="Enter your email address" class="w-80 h-20 p-3 bg-white mt-8 rounded-l-md">
                <button class="w-40 h-20 ml-1 bg-orange-500 rounded-r-md">SUBCRIBE</button>
            </div>
        </div>
        <img src="../../../assets/about-img.svg" alt="">
    </div>
  </div>
</template>

<script lang="ts">
export default {
    name: 'formComponent',
}
</script>

<style scoped>
    div#form {
        margin-top: 300px;
        background: linear-gradient(162.8deg, rgba(51, 164, 174, 0.671) 11.82%, rgba(6, 194, 175, 0.401) 122.39%);
        border-radius: 5px;
    }

</style>