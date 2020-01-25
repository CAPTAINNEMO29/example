<template>
  <section class="top-container">
    <div class="container d-flex justifycontent-center d-block w-100">
      <img
        @click="example"
        class="blockchain"
        src="images/blockchain-3277336_640.png"
        alt="Blockchain"
      />
      <h1 v-if="showCongrats">gracias por clickar</h1>
    </div>
  </section>
</template>

<script>
export default {
  name: "TopContainer"
};
</script>

<style scoped>
.portada {
  margin-bottom: 50px;
}
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
  width: 100vw;
  height: 55%;
  margin-bottom: 80px;
}
</style>
