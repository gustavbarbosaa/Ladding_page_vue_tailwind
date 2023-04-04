<template>
  <headerComponent />
  <homeComponent />
  <categoryComponent />
  <halloweenComponent />
</template>

<script>
import headerComponent from './components/Header/index.vue';
import homeComponent from './components/Body/Home/index.vue';
import categoryComponent from './components/Body/Category/index.vue';
import halloweenComponent from './components/Body/Halloween/index.vue';

export default {
  components: {
    headerComponent,
    homeComponent,
    categoryComponent,
    halloweenComponent,
  }
}
</script>

<style>

</style>