<template>
  <div class="container4">
    <div class="container4_header_box">
      <h1>Recent projects</h1>
      <hr />
    </div>
    <div class="container4_main">
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (5).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>woods</h1>
          <h2>Photography</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (6).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>path</h1>
          <h2>Website • Photography</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (7).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>darkness</h1>
          <h2>Website</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (8).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>waves</h1>
          <h2>Photography</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (9).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>drops</h1>
          <h2>Website</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (10).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>ocean</h1>
          <h2>Website</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (11).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>town</h1>
          <h2>Website</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (12).jpg')" alt="" />
        <div class="container4_main_box_text">
          <h1>mountain</h1>
          <h2>Website</h2>
        </div>
      </div>
      <div class="container4_main_box">
        <img :src="require('../assets/img/IMAGE (13).png')" alt="" />
        <div class="container4_main_box_text">
          <h1>camera</h1>
          <h2>Website</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Vollkorn&display=swap");
.container4 {
  width: 100%;
  height: 180vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  margin-top: 10px;
  background: #f5f5f5;
}

.container4_header_box {
  margin-bottom: 70px;
}

.container4 img{
    width: 100%;
}

.container4_header_box h1 {
  color: #333;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px;
  text-transform: uppercase;
}

.container4_header_box hr {
  width: 80px;
  border: 1px solid #d4d4d4;
  margin-left: 70px;
  margin-top: 40px;
}

.container4_main {
  width: 80%;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  align-content: center;
  gap: 2%;
}

.container4_main_box {
  width: 25%;
  height: 400px;
  text-align: center;
  margin-top: 90px;
  transition: all 0.3s linear;
}

.container4_main_box:hover {
  scale: 0.9;
}

.container4_main_box h1 {
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

.container4_main_box h2 {
  color: #333;
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
}

.container4_main_box_text {
  margin: auto;
  height: 70px;
  width: 100%;
  background-color: #fff;
  padding-top: 10px;
}
</style>
