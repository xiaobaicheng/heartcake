<template>
  <nav>
    <div class="logo">
      <img src="./assets/logo.png" alt="" />
    </div>
    <div class="head">
      <router-link to="/">首页</router-link>
      <router-link to="/about">蛋糕</router-link>
      <router-link to="/b">全国配</router-link>
      <router-link to="/c">蛋糕</router-link>
      <router-link to="/d">蛋糕</router-link>
    </div>
  </nav>
  <router-view />
</template>

<style lang="scss" scoped>
// #app {
// }

nav {
  height: 10vh;
  line-height: 10vh;
  width: 100%;
  display: flex;
  outline: 1px black solid;
 .logo{
  margin-left: 40px;
 }
  .head {
    width: 30%;
    display: flex;
    justify-content: space-around;
    outline: 1px black solid;
    a {
      color: black;
      text-decoration: none;
    }
    .router-link-active {
      color: red;
      // font-weight: 800;
      font-style: italic;
      // font-size: 80px;
      text-decoration: underline;
      // background-color: green;
    }
    height: 100%;
  }
}

</style>