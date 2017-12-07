<template>
  <div id="app">
    <c-header></c-header>
      <router-view/>
  </div>
</template>

<script>
import cHeader from '@/components/header'
export default {
  name: 'app',
  components: {
    cHeader
  }
}
</script>

<style lang="less">
  html, body {
    height: 100%;
    overflow: hidden;
  }
  body {
    background: #0a0a0a;
    background-image: -webkit-linear-gradient(#0f0f0f 1px, transparent 1px), -webkit-linear-gradient(left, #0f0f0f 1px, transparent 1px);
    background-image: linear-gradient(#0f0f0f 1px, transparent 1px), linear-gradient(to right, #0f0f0f 1px, transparent 1px);
    background-size: 3.33333vmin 3.33333vmin;
  }

#app {

}
</style>
