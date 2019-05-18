<template>
  <section class="middle-container">
    <div class="profile">
      <img
        class="picture-profile"
        src="images/_MG_5604.JPG"
        alt="personal picture"
      />
      <div class="profile__info">
        <h2>Hello.</h2>
        <p>This is my first web page.</p>
      </div>
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
</style>
