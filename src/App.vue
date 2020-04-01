<template>
  <div id="app">
    <div>
      <Top/>
    </div>
    <div class="left"></div>
    <div class="right"></div>
    <div class="bottom"></div>
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
  html, body {
    height: 100%;
    width: 100%;
    margin: 0;
    padding: 0;
  }
  ul, li {
    padding:0;
    margin:0;
    list-style:none
  }
  input {
    outline: none;
    border: none;
  }
  #app {
    width: 100vw;
    height: 100vh;
  }
  .left {
    width: 19vw;
    height: 86vh;
    background-color: #f5f5f7;
    float: left;
  }
  .right {
    width: 81vw;
    height: 86vh;
    background-color: #fafafa;
    float: left;
  }
  .bottom {
    float: left;
    width: 100vw;
    height: 7vh;
    background-color: red;
  }

</style>
