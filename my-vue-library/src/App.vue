<template>
  <shahab-banner>
    This is the sample component banner
  </shahab-banner>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// @ts-ignore
import ShahabBanner from './components/Banner.vue';

export default defineComponent({
  name: 'App',
  components: {
    'shahab-banner': ShahabBanner
  }
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
