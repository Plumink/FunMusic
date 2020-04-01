<template>
  <div class="top">
    <img src="../../assets/images/logo.png" alt="logo">
    <span>网易云音乐</span>
    <input type="text"
      value=""
      placeholder="请输入要搜索的内容"
    >
    <i class="fun-lvsousuo icon1"></i>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .top {
      width: 100vw;
      height: 7vh;
      background-color: #c62f2f;
    }
  .top>img:first-child {
    float: left;
    width: 2vw;
    border-radius: 2vw;
    margin-top: 2vh;
    margin-left: 3vw;
  }
  .top>span {
    width: 4vw;
    font-size: 20px;
    color: aliceblue;
    line-height: 7vh;
    padding-left: 1vw;
  }
  .top>input {
    width: 15vw;
    height: 3vh;
    background-color: #a82828;
    border-radius: 2vw;
    margin-left: 10vw;
    color: aliceblue;
    text-indent: 10px;
  }
  .top>input::-webkit-input-placeholder {
    color: #c77373;
    font-size: 14;
  }
  .icon1 {
    color: #c77373;
    display: inline-block;
    position: absolute;
    top: 2.8vh;
    left: 36vw;

  }

  
</style>
