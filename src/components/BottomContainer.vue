<template>
  <section class="bottom-container">
    <a class="footer-link" href="https://nakamotoinstitute.org/"
      >Satoshi Nakamoto Institute</a
    >
    <a class="footer-link" href="https://bitcointalk.org/">Bitcointalk</a>
    <a class="footer-link" href="https://www.reddit.com/r/Bitcoin/">Reddit</a>
    <p>© 2019 Growth Togheter</p>
  </section>
</template>

<script>
export default {
  name: "BottomContainer"
};
</script>

<style scoped>
.bottom-container {
  /*background-color: #f6e79c;*/
  background-color: #c2bece;
  width: 80%;
  height: 40%;
  display: inline-block;
}

.footer-link {
  text-align: center;
  font-size: 22px;
  padding: 10%;
}

@media (max-width: 1020px) {
  .footer-link {
    text-align: center;
    padding: 5%;
  }
}
</style>
