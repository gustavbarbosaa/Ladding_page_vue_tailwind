<template>
  <headerComponent />
  <homeComponent />
  <categoryComponent />
</template>

<script>
import headerComponent from './components/Header/index.vue';
import homeComponent from './components/Body/Home/index.vue';
import categoryComponent from './components/Body/Category/index.vue';

export default {
  components: {
    headerComponent,
    homeComponent,
    categoryComponent,
  }
}
</script>

<style>

</style>