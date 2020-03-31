<template>
  <div id="app">
    <div class="top">
      <Top/>
    </div>
    <div class="left"></div>
    <div class="right"></div>
  </div>
</template>

<script>
import Top from './components/head/Top';

export default {
  components: {Top}

}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
  }
  #app {
    width: 100vw;
    height: 100vh;
    background-color: cadetblue;
  }
  .top {
    width: 100vw;
    height: 7vh;
    background-color: #c62f2f;
  }
  .left {
    width: 19vw;
    height: 93vh;
    background-color: #f5f5f7;
    float: left;
  }
  .right {
    width: 81vw;
    height: 93vh;
    background-color: #fafafa;
    float: left;
  }

</style>
