<template>
  <section class="middle-container">
    <div class="container">
      <div class="row">
        <div class="col-sm-8 col-md-8 col-lg-6 mx-auto  text-center">
          <div id="example" class="carousel slide mt-4" data-ride="carousel">
            <ul class="carousel-indicators">
              <li data-target="#example" data-slide-to="0" class="active"></li>
              <li data-target="#example" data-slide-to="1"></li>
            </ul>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img
                  src="images/andre-francois-mckenzie-JrjhtBJ-pGU-unsplash.jpg"
                  alt="project"
                  class="d-block w-100"
                />
              </div>
              <div class="carousel-item">
                <img
                  src="images/clifford-photography-hiFghSs4keM-unsplash.jpg"
                  alt="project"
                  class="d-block w-100"
                />
              </div>
            </div>
            <a href="#example" class="carousel-control-prev" data-slide="prev">
              <span class="carousel-control-prev-icon"></span>
            </a>
            <a href="#example" class="carousel-control-next" data-slide="next">
              <span class="carousel-control-next-icon"></span>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col text-center">
          <h1 class=" text-dark ">
            <strong>Noticias actuales</strong>
          </h1>
          <router-link class="atribute" to="/Articulos">Noticias</router-link>
        </div>
      </div>
      <div class="row py-3">
        <div class="col-6 text-center">
          <h3 class="">Bitcoin</h3>
          <p class="text-muted"></p>
          <router-link class="atribute" to="/Bitcoin">Bitcoin</router-link>
        </div>
        <div class="col-6 text-center">
          <h3 class="">Ethereum</h3>
          <p class="text-muted"></p>
          <router-link class="atribute" to="/Ethereum">Ethereum</router-link>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MiddleContainer"
};
</script>

<style scoped>
.middle-container {
  background-color: #b7fbff;
  width: 100%;
  height: 40%;
  display: inline-block;
}

.profile {
  background-color: aqua;
  font-family: "Times New Roman", Times, serif;
  display: flex;
  padding: 50px 20px;
  align-items: center;
}

.profile__info {
  flex: 1;
}

.skills {
  display: flex;
  padding: 15px 15px;
}

.skill-row {
  flex: 1;
}

.btn {
  background: #1090e6;
  background-image: -webkit-linear-gradient(top, #1090e6, #0d6da8);
  background-image: -moz-linear-gradient(top, #1090e6, #0d6da8);
  background-image: -ms-linear-gradient(top, #1090e6, #0d6da8);
  background-image: -o-linear-gradient(top, #1090e6, #0d6da8);
  background-image: linear-gradient(to bottom, #1090e6, #0d6da8);
  -webkit-border-radius: 28;
  -moz-border-radius: 28;
  border-radius: 28px;
  font-family: Arial;
  color: #ffffff;
  font-size: 18px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}

.butn:hover {
  background: #3cb0fd;
  background-image: -webkit-linear-gradient(top, #3cb0fd, #3498db);
  background-image: -moz-linear-gradient(top, #3cb0fd, #3498db);
  background-image: -ms-linear-gradient(top, #3cb0fd, #3498db);
  background-image: -o-linear-gradient(top, #3cb0fd, #3498db);
  background-image: linear-gradient(to bottom, #3cb0fd, #3498db);
  text-decoration: none;
}

.picture-profile {
  width: 30%;
  height: 20%;
  border-radius: 100%;
}

.atribute {
  text-align: center;
  font-size: 22px;
}

@media (max-width: 640px) {
  .profile_info {
    text-align: bottom;
    flex: 0;
  }

  .picture-profile {
    position: static;
    width: 40%;
    height: 30%;
    border-radius: 100%;
  }
}
</style>
