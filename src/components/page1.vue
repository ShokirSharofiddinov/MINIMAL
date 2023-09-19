<template>
  <title>Shokir Sharofiddinov</title>
  <header>
    <div class="logo">
      <a href="#"
        ><img :src="require('../assets/img/IMAGE (2).jpg')" alt="Logo"
      /></a>
      <h3 class="logo_text">MINIMAL</h3>
    </div>
    <ul>
      <li><a href="/procces">process</a></li>
      <li><a href="/projects">projects</a></li>
      <li><a href="/team">team</a></li>
      <li><a href="/contact">contact</a></li>
    </ul>
  </header>
  <div class="container1">
    <h3 class="container1_box1">Making brands stand out is our obsession</h3>
    <hr />
    <p>Let us help your brand stand out.</p>
    <img
      :src="require('../assets/img/IMAGE (1).svg')"
      alt="x p"
      class="x_img"
    />
  </div>
  <div class="container2">
    <p>
      Minimalist is a full-service digital creative agency located in Ontario,
      Canada. We focus on design, consulting, technology, and photography. We've
      been building unique digital products, platforms, and experiences for the
      past 6 years. Let us help your company grow.
    </p>
    <button>Get in Touch</button>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Vollkorn&display=swap");
* {
  margin: 0;
  padding: 0;
}

header {
  display: flex;
  align-items: center;
  justify-content: space-around;
  height: 90px;
  width: 100%;
  gap: 50px;
}

.logo img {
  width: 90%;
}

.logo {
  height: 100%;
  display: flex;
  align-items: center;
}

.logo_text {
  color: #333;
  font-family: "Oswald", sans-serif;
  font-size: 22px;
  font-style: normal;
  font-weight: 400;
  line-height: 38px;
  text-transform: uppercase;
  margin-left: 25px;
}

ul {
  text-transform: uppercase;
  list-style-type: none;
  margin: 0;
  padding: 0;
  color: #585858;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}

li {
  display: inline;
  margin-right: 34px;
  color: #5d5d5d;
}

li a {
  color: #000000;
  font-family: "Montserrat", sans-serif;
  font-size: 13px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
  text-decoration: none;
}

li a:hover {
  color: rgb(0, 110, 157);
}

/* container 1 */

.container1 {
  width: 100%;
  height: 470px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  background-image: url("../assets/img/IMAGE\ \(3\).jpg");
  background-size: cover;
  margin-top: 10px;
}

.container1_box1 {
  color: #fff;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-size: 44px;
  font-style: normal;
  font-weight: 300;
  line-height: 55px; /* 125% */
  text-transform: uppercase;
  width: 672px;
  margin-bottom: 30px;
  margin-top: 40px;
}

.container1 hr {
  width: 70px;
  border: 0.9px solid white;
  margin-bottom: 30px;
}

.container1 p {
  color: rgba(255, 255, 255, 0.81);
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
}

.x_img {
  position: relative;
  background: url("../assets/img/IMAGE (3).jpg"),
    lightgray 50% / cover no-repeat;
  opacity: 1;
  top: 120px;
}

/* container 2 */

.container2 {
  height: 289px;
  background-color: #fefec9;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 40px;
  padding: 0 300px;
}

.container2 button {
  width: 159px;
  height: 53px;
  flex-shrink: 0;
  background-color: #fefec9;
  color: #47474f;
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  border: 2px solid gray;
  line-height: 20px;
  transition: all 0.2s linear;
}

.container2 button:hover {
  border-radius: 25px;
  background-color: rgb(153, 153, 153);
  color: #fefec9;
}

.container2 p {
  width: 870px;
  color: #47474f;
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 25px;
}
</style>
