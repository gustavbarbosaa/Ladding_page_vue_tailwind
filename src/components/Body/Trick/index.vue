<template>
  <div id="trick" class="flex flex-col items-center">
    <h1 class="text-white text-6xl font-noto font-bold text-center pb-40">Trick Or Treat</h1>
    <div class="grid gap-14 grid-cols-3 grid-rows-3">
        <div class="card-trick">
            <img src="../../../assets/tor1-img.svg" alt="">
            <h2>Candy</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur.</p>
        </div>
        <div class="card-trick">
            <img src="../../../assets/tor2-img.svg" alt="">
            <h2>Ghost</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur. </p>
        </div>
        <div class="card-trick">
            <img src="../../../assets/tor3-img.svg" alt="">
            <h2>Grave</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur. </p>
        </div>
        <div class="card-trick">
            <img src="../../../assets/tor4-img.svg" alt="">
            <h2>House</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur.</p>
        </div>
        <div class="card-trick">
            <img src="../../../assets/tor5-img.svg" alt="">
            <h2>Spider</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur.</p>
        </div>
        <div class="card-trick">
            <img src="../../../assets/tor-6-img.svg" alt="">
            <h2>Bone</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur.</p>
        </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
    name: 'trickComponent',
}
</script>

<style scoped>

    .card-trick {
        width: 308.57px;
        height: 360px;
        padding: 2rem;
        display: flex;
        flex-direction: column;
        align-items: center;
        border-radius: 5px;
        background: linear-gradient(171.09deg, rgba(51, 164, 174, 0.3) 6.77%, rgba(6, 194, 174, 0) 171.33%);
        transition: all ease-in-out .2s;
    }

    .card-trick:hover {
        transform: scale(1.2);
        background: linear-gradient(171.09deg, #33A4AE 6.77%, rgba(6, 194, 174, 0) 171.33%);
    }

    div img {
        width: 177px;
        height: 177px;
    }

    div h2 {
        color: white;
        font-weight: 500;
        font-size: 30px;
        font-family: Poppins;
    }

    div p {
        color: white;
        text-align: center;
        font-size: 13px;
        font-weight: 400;
        font-family: Roboto;
    }
</style>
