<template>
  <h4 class="about">.01 ABOUT US</h4>
  <div class="about-container">
    <div class="writeUp">
      <h2 class="heading">#1 DANCE <br />STUDIO.</h2>
      <p class="description">
        Aeromint Studio is a dance school <br />established in 1999. We aim to
        provide all<br />
        students with the understanding and an<br />
        insight into both technique and<br />
        choreography to prepare them for the<br />
        professional sector.
      </p>
      <DanceButton />
      <!-- <button class="btn">Learn more</button> -->
    </div>
    <div class="img">
      <img
        style="width: 70%; height: auto"
        src="/static/boy-dancing.png"
        alt="boy dancing"
      />
    </div>
  </div>
</template>

<style scooped>
.about-container {
  display: flex;
  margin-left: 25%;

  /* margin-right: 25%; */
  /* align-items: center; */
}
.writeUp {
  margin-top: 8%;
  margin-left: 20px;
}
.img {
  margin-left: 10px;
}
.heading {
  font-size: 60px;
  font-weight: bold;
  margin-top: 5%;
  margin-bottom: 6%;
  word-spacing: 5px;
  letter-spacing: 7px;
}
.about {
  margin-left: 25%;
}
.description {
  margin-left: 30px;
  font-size: 1.2rem;
  word-spacing: 3px;
  letter-spacing: 1px;
  opacity: 0.5;
}
</style>
