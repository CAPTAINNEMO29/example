<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
body {
  color: #40514e;
  margin: auto;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
}

h1 {
  font-size: 1.625rem;
  margin: 30px auto;
  padding-top: 25px;
  color: #7572f4;
  font-family: Arial, Helvetica, sans-serif;
  line-height: 2;
}

h2 {
  margin: 25px auto;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 1, 3rem;
  color: #c46812;
  font-weight: normal;
}

p {
  margin: 0;
  padding-bottom: 3%;
}

hr {
  border: dotted rgb(11, 146, 146) 6px;
  border-bottom: none;
  width: 4%;
  margin: 25px auto;
}

a {
  color: #3cb0fd;
  font-family: "Times New Roman", Times, serif;
  margin: 10px 20px;
  text-decoration: none;
}

a:hover {
  color: #e95b19;
}
</style>
