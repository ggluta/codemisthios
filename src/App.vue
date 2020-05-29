/* eslint-disable import/extensions */
<template>
  <div id="app">
    <lottie-player
      class="lottie-animtation"
      autoplay
      loop
      mode="normal"
      src='https://assets6.lottiefiles.com/packages/lf20_MAiPvC.json'>
    </lottie-player>
  </div>
</template>

<script>
import '@lottiefiles/lottie-player';

export default {
  components: {
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  background-color: #FFFFFF;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100vh;
}

.lottie-aniamtion {
  width: 100%;
  height: 100vh;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
