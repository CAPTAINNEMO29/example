<template>
  <div id="app">
    <TopContainer />
    <MiddleContainer />
    <BottomContainer />
  </div>
</template>

<script>
import TopContainer from "../components/TopContainer.vue";
import MiddleContainer from "../components/MiddleContainer.vue";
import BottomContainer from "../components/BottomContainer.vue";

export default {
  name: "app",
  components: {
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
