<template>
  <section class="top-container">
    <img
      @click="example"
      class="blockchain"
      src="images/blockchain-3277336_640.png"
      alt="Blockchain"
    />
    <h1 v-if="showCongrats">gracias por clickar</h1>
    <h1></h1>
    <p></p>
    <!--<img class="left-chain" src="file:///C:/Users/Pc/Desktop/web%20development/WEB%20Design/images/blockchain-3750157_640%20(1).jpg" alt="cadena">
        <img class="right-chain" src="file:///C:/Users/Pc/Desktop/web%20development/WEB%20Design/images/blockchain-3750157_640%20(1).jpg" alt="cadena">-->
  </section>
</template>

<script>
export default {
  name: "TopContainer"
};
</script>

<style scoped>
.top-container {
  background-color: #dfddc7;
  position: relative;
  padding-top: 100px;
  width: 100%;
}

p {
  margin: 0;
}

.blockchain {
  position: relative;
  margin: auto;
  width: 70%;
  height: 45%;
}
</style>
