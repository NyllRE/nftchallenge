<script>
export default {
  name: "App",
}
</script>

<template>
  <div class="container">
    <div class="card">
      <img src="./images/image-equilibrium.jpg" alt="" srcset="" />

      <h1>Equilibrium #3429</h1>

      <h4 class="color1">
        Our Equilibrium collection promotes balance and calm.
      </h4>

      <div class="price-time">
        <span>
          <svg width="11" height="18" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M11 10.216 5.5 18 0 10.216l5.5 3.263 5.5-3.262ZM5.5 0l5.496 9.169L5.5 12.43 0 9.17 5.5 0Z"
              fill="#00FFF8"
            />
          </svg>
          <b class="color2">0.041 ETH</b>
        </span>

        <span id="time">
          <svg width="17" height="17" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M8.305 2.007a6.667 6.667 0 1 0 0 13.334 6.667 6.667 0 0 0 0-13.334Zm2.667 7.334H8.305a.667.667 0 0 1-.667-.667V6.007a.667.667 0 0 1 1.334 0v2h2a.667.667 0 0 1 0 1.334Z"
              fill="#8BACD9"
            />
          </svg>
          <span class="color1">3 days left</span>
        </span>
      </div>

      <hr />

      <div class="creator">
        <img src="./images/image-avatar.png" alt="avatar" srcset="" />
        <span>
          <span class="color1"> Creation of </span>

          <b> Jules Wyvern </b>
        </span>
      </div>
    </div>
  </div>

  <div id="attribution"></div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  color: white;
  font-family: "Outfit", sans-serif;
  background: hsl(217, 54%, 11%);
  height: 100vh;
}

.card {
  width: 300px; height: 510px;
  background: hsl(216, 50%, 16%);
  padding: 20px;
  border-radius: 12px;

  position: absolute;
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  
  font-size: 0.78em;
  box-shadow: 0 0 50px #0005;
}

.card > * {
  margin-top: 18px;
}

.card > img {
  width: 260px;
  border-radius: 9px;
  margin: 0;
}

.card h1 {
  font-size: 1.5em;
}

.color1 {
  color: hsl(215, 51%, 70%);
}

.color2 {
  color: hsl(178, 100%, 50%);
  font-weight: 600;
}

.card h4 {
  font-size: 1.2em;
  font-weight: 300;
}

.price-time {
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-size: 1.08em
}

.price-time span {
  display: flex;
  align-items: center;
  gap: 5px;
}

hr {
  background-color: hsl(215, 32%, 27%);
  width: 100%;
  height: 1px;
  border: none;
  /* border-radius: 10px; */
  margin: 15px 0;
}

.creator {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 1.1em;
  margin-top: 9px;
}

.creator img {
  width: 30px;
  border: solid 1px #fff;
  border-radius: 50%;
}

b {
  font-weight: 400
}
</style>
