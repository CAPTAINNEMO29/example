<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <TopContainer/>
    <MiddleContainer/>
    <BottomContainer/>
  </div>

</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import TopContainer from "./components/TopContainer.vue"
import MiddleContainer from "./components/MiddleContainer.vue"
import BottomContainer from "./components/BottomContainer.vue"

export default {
  name: "app",
  components: {
    //HelloWorld
    TopContainer,
    MiddleContainer,
    BottomContainer
  },
  data: () => ({
    showCongrats: false
  }),
  methods: {
    example() {
      this.showCongrats = !this.showCongrats;
    }
  }
};
</script>

<style>
body {
  margin: auto;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
}

h1 {
  margin: 0 auto;
  padding-top: 25px;
}

h2 {
  margin: 0 auto;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.blockchain {
  position: relative;
  margin: auto;
  width: 70%;
  height: 45%;
}





.pro {
  text-decoration: underline;
}

/*.left-chain{
  position: absolute;
  right: 70%;
  top: 30%;
}

/*.right-chain{
  position: absolute;
  top: 30%;
  left: 70%;
}

*/



.skills {
}

.picture-profile {
  width: 30%;
  height: 20%;
}
</style>
