<template>
  <div class="ballet-container">
    <div>
      <h1 class="ballet-heading">
        <span class="b">B</span>ALLET<br />
        <span class="d">DANCE</span>
      </h1>
      <div class="image-container">
        <img
          class="ballet-image"
          src="/static/ballet.png"
          alt="ballet dance lesson"
        />
      </div>
    </div>
    <div>
      <p class="ballet-description">
        Ballet is a beautiful and demanding art form that originated in<br />
        Renaissance Italy. It combines athleticism and artistry, <br />requiring
        dancers to possess incredible flexibility, <br />
        strength, and coordination. Ballet dancers tell stories through their<br />
        bodies, using precise movements and elegant poses to <br />express
        emotions and ideas.<br />
        Below are a list of songs for ballet dancing.
      </p>
      <ul class="list">
        <li>
          <span class="songs">Swan Lake</span> by Pyotr Ilyich Tchaikovsky
        </li>
        <li><span class="songs">Giselle </span>by Adolphe Adam</li>
        <li>
          <span class="songs">Sleeping Beauty </span>by Pyotr Ilyich Tchaikovsky
        </li>
      </ul>
      <DanceButton />
      <!-- <button class="ballet">Larn more</button> -->
    </div>
  </div>
  <div class="ballet-container">
    <div>
      <p class="jazz-description">
        Ballet is a beautiful and demanding art form that originated in<br />
        Renaissance Italy. It combines athleticism and artistry, <br />requiring
        dancers to possess incredible flexibility, <br />
        strength, and coordination. Ballet dancers tell stories through their<br />
        bodies, using precise movements and elegant poses to <br />express
        emotions and ideas.<br />
        Below are a list of songs for ballet dancing.
      </p>
      <ul class="list">
        <li>
          <span class="songs">Swan Lake</span> by Pyotr Ilyich Tchaikovsky
        </li>
        <li><span class="songs">Giselle </span>by Adolphe Adam</li>
        <li>
          <span class="songs">Sleeping Beauty </span>by Pyotr Ilyich Tchaikovsky
        </li>
      </ul>
      <DanceButton />
    </div>
    <div>
      <div class="image-container">
        <h1 class="jazz-heading"><span class="j">J</span>AZZ-FUNK</h1>
        <img
          class="jazz-image"
          src="/static/jazz.png"
          alt="jazz dance lesson"
        />
      </div>
    </div>
  </div>
  <div class="ballet-container">
    <div>
      <h1 class="pop-heading">
        <span class="h">H</span>IP<br />
        <span class="pop">HOP</span>
      </h1>
      <div class="image-container">
        <img
          class="pop-image"
          src="/static/hip-pop.png"
          alt="ballet dance lesson"
        />
      </div>
    </div>
    <div>
      <p class="ballet-description">
        Ballet is a beautiful and demanding art form that originated in<br />
        Renaissance Italy. It combines athleticism and artistry, <br />requiring
        dancers to possess incredible flexibility, <br />
        strength, and coordination. Ballet dancers tell stories through their<br />
        bodies, using precise movements and elegant poses to <br />express
        emotions and ideas.<br />
        Below are a list of songs for ballet dancing.
      </p>
      <ul class="list">
        <li>
          <span class="songs">Swan Lake</span> by Pyotr Ilyich Tchaikovsky
        </li>
        <li><span class="songs">Giselle </span>by Adolphe Adam</li>
        <li>
          <span class="songs">Sleeping Beauty </span>by Pyotr Ilyich Tchaikovsky
        </li>
      </ul>
      <DanceButton />
      <!-- <button class="ballet">Larn more</button> -->
    </div>
  </div>
  <div class="ballet-container">
    <div>
      <p class="ballet-description">
        Ballet is a beautiful and demanding art form that originated in<br />
        Renaissance Italy. It combines athleticism and artistry, <br />requiring
        dancers to possess incredible flexibility, <br />
        strength, and coordination. Ballet dancers tell stories through their<br />
        bodies, using precise movements and elegant poses to <br />express
        emotions and ideas.<br />
        Below are a list of songs for ballet dancing.
      </p>
      <ul class="list">
        <li><span>Swan Lake</span> by Pyotr Ilyich Tchaikovsky</li>
        <li><span s>Giselle </span>by Adolphe Adam</li>
        <li><span>Sleeping Beauty </span>by Pyotr Ilyich Tchaikovsky</li>
      </ul>
      <DanceButton />
    </div>
    <div>
      <h1 class="jazz-heading"><span class="j">B</span>REAKDANCE</h1>
      <div class="image-container">
        <img
          class="jazz-image"
          src="/static/breakdance.png"
          alt="ballet dance lesson"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
.ballet-container {
  display: flex;
  margin-left: 20%;
}
.b {
  color: red;
  opacity: 0.5;
  font-weight: bold;
  font-size: 12rem;
  margin-bottom: 0;
}
.h {
  color: red;
  opacity: 0.5;
  font-weight: bold;
  font-size: 10rem;
}
.j {
  color: rgb(107, 91, 0);
  font-weight: bold;
  font-size: 10rem;
}
.songs {
  color: red;

  font-size: 1.2rem;
  word-spacing: 3px;
  letter-spacing: 1px;
}
.d {
  margin-top: 0;
  margin-left: 30%;
}
.ballet-heading {
  margin-left: 20%;
  font-size: 3rem;

  /* margin-bottom: 20%; */
}
.jazz-heading {
  margin-top: 40px;
  font-size: 4rem;

  /* margin-left: 0%; */
}
.pop-heading {
  margin-top: 100px;
  margin-left: 60%;
  font-size: 3rem;
}
.pop {
  margin-left: 55%;
}
.ballet-description {
  margin-top: 50%;
  margin-left: 30px;
  font-size: 1.2rem;
  word-spacing: 3px;
  letter-spacing: 1px;
  opacity: 0.5;
  /* margin-left: 10%; */
}
.jazz-description {
  margin-top: 40%;
  margin-left: 30px;
  font-size: 1.2rem;
  word-spacing: 3px;
  letter-spacing: 1px;
  opacity: 0.5;
}
.image-container {
  position: relative;
  width: 500px;
  height: 100px;
}
.ballet-image {
  position: absolute;
  top: 80%;
  left: 20%;
  transform: translate(-50%, -50%);
  /* min-width: 100%;
  min-height: 100%; */
  width: 718;
  height: 1130;
}
.jazz-image {
  position: absolute;
  top: 400%;
  left: 40%;
  transform: translate(-40%, -65%);
  /* width: 618;
  height: 1100; */
}
.pop-image {
  position: absolute;
  top: 90%;
  left: 40%;
  transform: translate(-40%, -40%);
  /* min-width: 100%;
  min-height: 100%; */
  width: 718;
  height: 1130;
}
.list {
  list-style-type: none;
  /* margin-left: 45%; */
  font-size: 1.2rem;
  word-spacing: 3px;
  letter-spacing: 1px;
  opacity: 0.5;
}
</style>
