<template>
  <headerComponent />
  <homeComponent />
  <categoryComponent />
  <halloweenComponent />
  <h1 class="text-white text-6xl font-noto font-bold text-center pb-40">Trick Or Treat</h1>
  <div class="grid gap-14 grid-cols-3 grid-rows-2">
    <trickComponent :img="img1" :title="title1" :text="text"/>
    <trickComponent :img="img2" :title="title2" :text="text"/>
    <trickComponent :img="img3" :title="title3" :text="text"/>
    <trickComponent :img="img4" :title="title4" :text="text"/>
    <trickComponent :img="img5" :title="title5" :text="text"/>
    <trickComponent :img="img6" :title="title6" :text="text"/>
  </div>
  <formComponent />
  <infosFooterComponent />
  <socialMediaComponent />
</template>

<script>
import headerComponent from './components/Header/index.vue';
import homeComponent from './components/Body/Home/index.vue';
import categoryComponent from './components/Body/Category/index.vue';
import halloweenComponent from './components/Body/Halloween/index.vue';
import trickComponent from './components/Body/Trick/index.vue';
import formComponent from './components/Body/Form/index.vue';
import infosFooterComponent from './components/Footer/Infos/index.vue';
import socialMediaComponent from './components/Footer/SocialMedia/index.vue';

export default {
  components: {
    headerComponent,
    homeComponent,
    categoryComponent,
    halloweenComponent,
    trickComponent,
    formComponent,
    infosFooterComponent,
    socialMediaComponent
  },
  data() {
    return {
      img1: 'src/assets/tor1-img.svg',
      img2: 'src/assets/tor2-img.svg',
      img3: 'src/assets/tor3-img.svg',
      img4: 'src/assets/tor4-img.svg',
      img5: 'src/assets/tor5-img.svg',
      img6: 'src/assets/tor-6-img.svg',
      title1: 'Candy',
      title2: 'Ghost',
      title3: 'Grave',
      title4: 'House',
      title5: 'Spider',
      title6: 'Bone',
      text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id id consequat, eu faucibus nulla. Ultrices mattis lacus, sed maecenas nascetur.'
    }
  }
}
</script>

<style>

</style>