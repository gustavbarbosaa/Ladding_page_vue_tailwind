<template>
  <headerComponent />
  <homeComponent />
</template>

<script>
import headerComponent from './components/Header/index.vue';
import homeComponent from './components/Body/index.vue';

export default {
  components: {
    headerComponent,
    homeComponent
  }
}
</script>

<style>

</style>