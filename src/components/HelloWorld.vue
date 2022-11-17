<script setup>
  import {reactive} from 'vue';
  import ShopFooter from './ShopFooter.vue';

  const state = reactive({title: '헬로월드'})
</script>

<template>
  <div>
    <input/>
    <button>{{state.title}}</button>
    <shop-footer></shop-footer>
  </div>
</template>

<style>
</style>