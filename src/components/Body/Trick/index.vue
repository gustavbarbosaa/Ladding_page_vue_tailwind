<template>
  <div id="trick" class="flex flex-col items-center">
        <div class="card-trick">
            <img :src="img" :alt="alt">
            <h2>{{title}}</h2>
            <p>{{text}}</p>
        </div>
  </div>
</template>

<script lang="ts">
export default {
    name: 'trickComponent',
    props: ['img', 'alt', 'title', 'text'],
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
