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
      <a href="https://www.youtube.com/watch?v=o-QA_AQNhm8"> <DanceButton /></a>

      <!-- <button class="ballet">Larn more</button> -->
    </div>
  </div>
  <div class="ballet-container">
    <div>
      <p class="jazz-description">
        Jazz Funk is a captivating dance style that blends the<br />
        dynamic energy of hip-hop with the smooth expressiveness<br />
        of jazz dance. It emerged from street corners and nightclubs,<br />
        creating a space for dancers to showcase their individuality <br />and
        creativity. Below are songs one can use
      </p>
      <ul class="list">
        <li><span class="songs">Get Up</span> by James Brown</li>
        <li><span class="songs">Rapture </span>by Blondie</li>
        <li>
          <span class="songs">Can't stop the feeling</span>by Pyotr Justin
          Timberlake
        </li>
      </ul>
      <a href="https://www.youtube.com/watch?v=ZUcVdhAAmSE"> <DanceButton /></a>
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
        Hip hop dance is a dynamic and expressive art <br />form born on the
        streets. It's a powerful mix<br />
        of athleticism, musicality, and personal style. From popping <br />and
        locking to breaking and breaking, hip hop dance allows<br />
        dancers to tell stories and express themselves<br />
        through movement. Below are a list of songs for ballet dancing.
      </p>
      <ul class="list">
        <li><span class="songs">Hot in Herre</span> by Nelly</li>
        <li><span class="songs">Crazy in Love </span>by Beyoncé ft. Jay-Z</li>
        <li>
          <span class="songs">Can't Hold Us </span>by Macklemore & Ryan Lewis
        </li>
      </ul>
      <a href="https://www.youtube.com/watch?v=h3DSYn2jIKE"> <DanceButton /></a>

      <!-- <button class="ballet">Larn more</button> -->
    </div>
  </div>
  <div class="ballet-container">
    <div>
      <p class="ballet-description">
        Breakdancing, also known as b-boying or breaking, is an explosive<br />
        and acrobatic dance style. It originated on the streets as part of<br />
        hip hop culture and has evolved into a physically demanding<br />
        and visually stunning art form. Breakdancing features dynamic floor
        work<br />
        like headstands, freezes, and power moves that defy gravity.<br />
        Below are a list of songs for ballet dancing.
      </p>
      <ul class="list">
        <li>
          <span class="songs">Planet Rock</span> by Afrika Bambaataa & The
          Soulsonic Force
        </li>
        <li><span class="songs">Apache</span>by The Incredible Bongo Band</li>
        <li><span class="songs">Pump Up the Jam</span>by Technotronic</li>
      </ul>
      <a href="https://www.youtube.com/watch?v=WB7QQl2_GQY"> <DanceButton /></a>
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
/* .list li {
  margin-left: 20%;
} */
.list {
  list-style-type: none;
  /* margin-left: 45%; */
  font-size: 1.2rem;
  word-spacing: 3px;
  letter-spacing: 1px;
  opacity: 0.5;
}
</style>
