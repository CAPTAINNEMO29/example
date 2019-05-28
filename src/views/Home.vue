<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <TopContainer />
    <MiddleContainer />
    <BottomContainer />
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import TopContainer from "../components/TopContainer.vue";
import MiddleContainer from "../components/MiddleContainer.vue";
import BottomContainer from "../components/BottomContainer.vue";

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
