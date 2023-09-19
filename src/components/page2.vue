<template>
  <div class="container3">
    <div class="container3_header_box">
      <h1>How we make brands thrive</h1>
      <hr />
    </div>
    <div class="container3_main">
      <div class="container3_main_box">
        <img
          :src="require('../assets/img/Screenshot 2023-09-18 at 08.07.46.png')"
          alt="target img"
        />

        <h2>SET a target</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
          varius enim in eros elementum tristique.
        </p>
      </div>
      <div class="container3_main_box">
        <img
          :src="require('../assets/img/Screenshot 2023-09-18 at 08.08.22.png')"
          alt="design a solution img"
        />
        <h2>design a solution</h2>
        <p>
          Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut
          commodo diam libero vitae erat.
        </p>
      </div>
      <div class="container3_main_box">
        <img
          :src="require('../assets/img/Screenshot 2023-09-18 at 08.08.39.png')"
          alt="track the progress img"
        />
        <h2>track the progress</h2>
        <p>
          Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet. Nunc
          ut sem vitae risus tristique posuere.
        </p>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Vollkorn&display=swap");
.container3 {
  width: 100%;
  height: 75vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  margin-top: 10px;
}

.container3_header_box {
  margin-bottom: 70px;
}

.container3_header_box h1 {
  color: #333;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-size: 23px;
  font-style: normal;
  font-weight: 400;
  line-height: 36px;
  text-transform: uppercase;
}

.container3_header_box hr {
  width: 80px;
  border: 1px solid #d4d4d4;
  margin-left: 140px;
  margin-top: 40px;
}

.container3_main {
  width: 100%;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  align-content: center;
  gap: 1%;
}

.container3_main_box {
  width: 16%;
  transition: all 0.3s linear;
}

.container3_main_box:hover {
  transform: scale(0.9);
}

.container3_main_box img {
  width: 100%;
  height: 219px;
  flex-shrink: 0;
}

.container3_main_box h2 {
  color: #333;
  text-align: center;
  font-family: "Montserrat", sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 20px;
  text-transform: uppercase;
  margin: 20px 0;
}

.container3_main_box p {
  color: #4d4d4d;
  text-align: center;
  font-family: "Vollkorn", serif;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 22px;
}
</style>
