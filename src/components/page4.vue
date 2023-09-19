<template>
  <div class="container">
    <div class="container_header_box">
      <h1>Our team</h1>
      <hr />
    </div>
    <div class="container_main">
      <div class="container_main_box">
        <img :src="require('../assets/img/person_img1.jpg')" alt="" />
        <h1>Ron Swanson</h1>
        <h2>Founder</h2>
        <img :src="require('../assets/img/twitter.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/in.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/mail.svg')" alt="" class="logo" />
      </div>
      <div class="container_main_box">
        <img :src="require('../assets/img/person_img2.jpg')" alt="" />
        <h1>Julia Depish</h1>
        <h2>Marketing</h2>
        <img :src="require('../assets/img/twitter.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/in.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/mail.svg')" alt="" class="logo" />
      </div>
      <div class="container_main_box">
        <img :src="require('../assets/img/person_img3.jpg')" alt="" />
        <h1>Danny Devry</h1>
        <h2>Designer</h2>
        <img :src="require('../assets/img/instagram.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/twitter.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/be.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/ball.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/mail.svg')" alt="" class="logo" />
      </div>
      <div class="container_main_box">
        <img :src="require('../assets/img/person_img4.png')" alt="" />
        <h1>Lisa Smith</h1>
        <h2>Developer</h2>
        <img :src="require('../assets/img/facebook.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/in.svg')" alt="" class="logo" />
        <img :src="require('../assets/img/mail.svg')" alt="" class="logo" />
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Vollkorn&display=swap");
.container {
  width: 100%;
  height: 75vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  margin-top: 10px;
}

.container_header_box {
  margin-bottom: 70px;
}

// .container img {
//   width: 100%;
// }

.container_header_box h1 {
  color: #333;
  text-align: center;
  font-family: "Montserrat", serif;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px; 
  text-transform: uppercase;
}

.container_header_box hr {
  width: 60px;
  border: 1px solid #d4d4d4;
  margin-left: 32px;
  margin-top: 40px;
}

.container_main {
  width: 80%;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  align-content: center;
  gap: 1%;
}

.container_main_box {
  width: 16%;
  height: 400px;
  text-align: center;
  margin-top: 20px;
  transition: all 0.3s linear;
}

.container_main_box:hover {
  scale: 0.9;
}

.container_main_box h1 {
  color: #333;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.container_main_box h2 {
  color: #333;
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
}

.logo {
  margin: 10px;
}
</style>
