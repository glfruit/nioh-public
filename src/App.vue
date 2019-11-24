<template>
  <div id="app">
    <home-list />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HomeList from './components/HomeList.vue';

@Component({
  components: {
    HomeList,
  },
})
export default class App extends Vue {}
</script>

<style>

</style>

