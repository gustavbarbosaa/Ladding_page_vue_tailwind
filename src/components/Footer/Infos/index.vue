<template>
  <div id="infos-footer" class="pl-44 pr-48 mt-48 flex justify-between">
    <div>
        <div class="flex items-center gap-2">
            <h2 class="font-bold font-roboto text-white text-2xl">Hallow<span class="text-orange-500">ee</span>nd</h2>
            <img src="../../../assets/img-header.svg" alt="">
        </div>
        <p class="max-w-md font-roboto font-normal text-lg text-white">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Elementum fringilla ultricies eget amet blandit quis sit duis. Suspendisse fames venenatis volutpat urna dui. Quisque non diam mi ullamcorper.
        </p>
        <img src="../../../assets/footer2-img.svg" alt="">
    </div>
    <div class="flex gap-20">
        <div>
            <h3 class="font-poppins font-medium text-xl text-white">About</h3>
            <p>About Us</p>
            <p>Feature</p>
            <p>Career</p>
        </div>
        <div>
            <h3>Company</h3>
            <p>Our Team</p>
            <p>Partnert</p>
            <p>Question</p>
        </div>
        <div>
            <h3>Service</h3>
            <p>Support</p>
            <p>Feedback</p>
            <p>Contact</p>
        </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
    name: 'infosFooterComponent'
}
</script>

<style scoped>

    div h3 {
        font-weight: 500;
        font-size: 20px;
        font-family: Poppins, sans-serif;
        color: white;
        padding: 1rem 0;
    }

    div p {
        font-weight: 400;
        font-size: 16px;
        font-family: Poppins, sans-serif;
        color: white;
        padding: .5rem 0;
    }

</style>