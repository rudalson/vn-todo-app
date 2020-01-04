<template>
  <view class="container">
    <Statusbar color="#00FF00"/>
    <text>Hello, World</text>
  </view>
</template>

<script>
  import Statusbar from './components/Statusbar';
  export default {
    components: {
      Statusbar
    }
  }
</script>

<style>
.container {
  background-color: white;
  flex: 1;
}
</style>
