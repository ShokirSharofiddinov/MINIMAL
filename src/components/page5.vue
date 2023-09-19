<template>
  <div class="container">
    <div class="container_header_box">
      <img :src="require('../assets/img/img.svg')" alt="" />
    </div>
    <div class="container_main">
      <div class="container_main_box" style="border-right: 2px solid lightgrey; padding: 30px;">
        <h2>
          “I love these guys! They did a great job. I would recommend them to
          anyone.”
        </h2>
        <img :src="require('../assets/img/person_img5.jpg')" alt="" />
        <p>Julius Von Uberstien</p>
      </div>
      <div class="container_main_box">
        <h2>
            “Elexis Corp. has grown immensely with the help of Minimal.”
        </h2>
        <img :src="require('../assets/img/person_img6.jpg')" alt="" />
        <p>Rachel Stamos</p>
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
  background: #f5f5f5;
}

.container_header_box {
  margin-bottom: 70px;
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
  width: 24%;
  height: 300px;
  text-align: center;
  margin-top: 20px;
  text-align: center;
  padding: 20px;
}

.container_main_box h2 {
  width: 338px;
  color: #333;
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 26px;
  font-style: normal;
  font-weight: 400;
  line-height: 33px;
}

.container_main_box p {
  color: #ababab;
  text-align: center;
  font-family: "Montserrat", serif;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
}
</style>
