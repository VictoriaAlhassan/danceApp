<template>
  <div class="home">
    <nav class="navbar">
      <div class="container">
        <div class="logo">
          <img src="/logo-multiple.png" alt="Logo" />
        </div>
        <ul>
          <a href="#home"> <li>Home</li></a>
          <a href="#about"><li>About</li></a>
          <a href="#category"><li>Category</li></a>
          <a href="#contact"><li>Contact</li></a>
        </ul>
      </div>
    </nav>
    <div class="hero" id="home">
      <div class="overlay"></div>
      <img class="dance-image" src="/dancing-lady.png" alt="Dancing Lady" />

      <div class="content">
        <h1>Welcome to Redeem Dance</h1>
        <p>Get ready to groove!</p>
      </div>
    </div>
    <div id="about">
      <DanceAbout />
    </div>
    <div id="category">
      <DanceBallet />
    </div>

    <div id="contact">
      <DanceContact />
    </div>
  </div>

  <footer>
    <p>© 2024 Redeem Dance Club. All Rights Reserved</p>
    <ul>
      <li><img src="" alt="" /></li>
      <li><img src="" alt="" /></li>
      <li><img src="" alt="" /></li>
    </ul>
  </footer>
</template>

<style scoped>
.home {
  position: relative;
}

.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #f8757e;
  z-index: 999;
}

.container {
  max-width: 960px;
  margin: 0 auto;
  padding: 10px 20px;
  display: flex;
  align-items: center;
}

.logo img {
  width: 50px; /* Adjust width as needed */
  height: auto; /* Maintains aspect ratio */
  position: absolute; /* Positions the logo */
  top: 50%;
  transform: translateY(-50%); /* Centers vertically */
  left: 0; /* Places it on the far left */
  margin-left: 10px;
}
.navbar ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  /* align-items: center; */
  margin-left: 90%;
}

.navbar ul li {
  margin-top: 30px;
  margin-left: 20px;
  font-size: 25px;
}

.navbar ul li a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
}
a {
  text-decoration: none;
  color: white;
}
a:hover {
  cursor: pointer;
  color: blue;
}

.hero {
  position: relative;
  height: 100vh;
  width: 100%;
  padding-top: 60px;
  overflow: hidden;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #f8757e;
}

.dance-image {
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translate(-50%, -50%);
  /* min-width: 100%;
  min-height: 100%; */
  width: 718;
  height: 1134;
  /* z-index: -1; */
}

.content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: #fff;
  font-size: 20px;
}
</style>

<script></script>
