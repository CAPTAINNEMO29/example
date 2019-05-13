<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <div class="top-container">
      <img
        @click="example"
        class="blockchain"
        src="images/blockchain-3277336_640.png"
        alt="Blockchain"
      />
      <h1 v-if="showCongrats">gracias por clickar</h1>
      <h1>I'm Antonio.</h1>
      <p>a <span class="pro">pro</span>grammer.</p>
      <!--<img class="left-chain" src="file:///C:/Users/Pc/Desktop/web%20development/WEB%20Design/images/blockchain-3750157_640%20(1).jpg" alt="cadena">
    <img class="right-chain" src="file:///C:/Users/Pc/Desktop/web%20development/WEB%20Design/images/blockchain-3750157_640%20(1).jpg" alt="cadena">-->
    </div>
    <div class="middle-container">
      <div class="profile">
        <img
          class="picture-profile"
          src="images/_MG_5604.JPG"
          alt="personal picture"
        />
        <h2>Hello.</h2>
        <p>This is my first web page.</p>
      </div>
      <hr />
      <div class="skills">
        <h2>My Skills.</h2>
        <div class="skill-row">
          <img class="" src="" alt="" />
          <h3>Web Design</h3>
          <p>my main objective now is web development</p>
        </div>
        <div class="skill-row">
          <img class="" src="" alt="" />
          <h3>Blockchain Development</h3>
          <p>my second skill is the development of blockchain</p>
        </div>
      </div>
      <hr />
      <div class="contact-me">
        <h2>Get In Touch</h2>
        <h3></h3>
        <p></p>
        <a class="btn" href="mailto:name@email.com">CONTACT ME</a>
        <hr />
      </div>
    </div>

    <div class="bottom-container">
      <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
      <a class="footer-link" href="https://twitter.com/">Twitter</a>
      <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
      <p>© 2019 Antonio Martinez</p>
    </div>
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    //HelloWorld
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

.top-container {
  background-color: #dfddc7;
  position: relative;
  padding-top: 100px;
  width: 100%;
}

.blockchain {
  position: relative;
  margin: auto;
  width: 70%;
  height: 45%;
}

.middle-container {
  background-color: #b7fbff;
  width: 80%;
  height: 40%;
  display: inline-block;
}

.bottom-container {
  background-color: #f6e79c;
  width: 80%;
  height: 40%;
  display: inline-block;
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

.profile {
  background-color: aqua;
  font-family: "Times New Roman", Times, serif;
}

.skills {
}

.picture-profile {
  width: 30%;
  height: 20%;
}
</style>
