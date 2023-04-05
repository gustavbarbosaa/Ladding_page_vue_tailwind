<template>
  <headerComponent />
  <homeComponent />
  <categoryComponent />
  <halloweenComponent />
  <trickComponent />
</template>

<script>
import headerComponent from './components/Header/index.vue';
import homeComponent from './components/Body/Home/index.vue';
import categoryComponent from './components/Body/Category/index.vue';
import halloweenComponent from './components/Body/Halloween/index.vue';
import trickComponent from './components/Body/Trick/index.vue';

export default {
  components: {
    headerComponent,
    homeComponent,
    categoryComponent,
    halloweenComponent,
    trickComponent,
  }
}
</script>

<style>

</style>