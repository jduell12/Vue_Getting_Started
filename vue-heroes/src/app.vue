<template>
  <div id="app">
    <HeaderBar />
    <div class="main-section columns">
      <h2 class="title">Heroes</h2>
    </div>
  </div>
</template>

<script>
import HeaderBar from '@/components/header-bar';

export default {
  name: 'App',
  components: { HeaderBar },
};
</script>

<style lang="scss">
@import '@/design/index.scss';
</style>
