<template>
  <section class="bottom-container">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-4 text-center py-3">
          <a class="footer-link " href="https://nakamotoinstitute.org/"
            >Satoshi Nakamoto Institute</a
          >
        </div>
        <div class="col-sm-12 col-md-4 text-center py-3">
          <a class="footer-link " href="https://bitcointalk.org/"
            >Bitcointalk</a
          >
        </div>
        <div class="col-sm-12 col-md-4 text-center py-3">
          <a class="footer-link " href="https://www.reddit.com/r/Bitcoin/"
            >Reddit</a
          >
        </div>
      </div>
    </div>
    <div class="">
      <p class=" text-center">© 2019 Growth Togheter</p>
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
