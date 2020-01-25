<template>
  <section class="bottom-container">
    <div class="container">
      <div class="row ">
        <div class="col text-center py-3">
          <a class="footer-link " href="https://nakamotoinstitute.org/"
            >Satoshi Nakamoto Institute</a
          >
          <a class="footer-link " href="https://bitcointalk.org/"
            >Bitcointalk</a
          >
          <a class="footer-link " href="https://www.reddit.com/r/Bitcoin/"
            >Reddit</a
          >
        </div>
      </div>
      <div class="row">
        <p class="col text-center">© 2019 Growth Togheter</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "BottomContainer"
};
</script>

<style scoped>
.bottom-container {
  background-color: #c2bece;
  width: 100%;
  height: 40%;
}

.a {
}

.footer-link {
  padding: 3px;
  margin: auto !important;
  width: 8vw;
}
</style>
