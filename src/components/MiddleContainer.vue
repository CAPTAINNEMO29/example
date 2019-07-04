<template>
  <section class="middle-container">
    <div class="profile">
      <img
        class="picture-profile"
        src="images/matrix-3109378_640.jpg"
        alt="personal picture"
      />
      <div class="profile__info">
        <h2>This tecnology was made for rule your own independency.</h2>
        <p></p>
      </div>
    </div>
    <hr />
    <div class="skills">
      <h2>What we learn.</h2>
      <div class="skill-row">
        <img class="" src="" alt="" />
        <h3>Web Design</h3>
        <p>We will learn about web design.</p>
      </div>
      <div class="skill-row">
        <img class="" src="" alt="" />
        <h3>Blockchain Development</h3>
        <p>Principals knowledges and news.</p>
      </div>
    </div>
    <hr />
    <div class="contact-me">
      <h2>First Articles.</h2>
      <router-link class="atribute" to="/ethereum">ethereum</router-link>
      <router-link class="atribute" to="/blockchain">blockchain</router-link>
      <h3>Get in Touch</h3>
      <p>Let's learn together.</p>
      <a class="btn" href="neofrom29@gmail.com">CONTACT ME</a>
      <hr />
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
  width: 80%;
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
  font-size: 20px;
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
</style>
