<template>
  <h4 class="second"><span class="underline">.02 CON</span>TACTS</h4>
  <div class="contact-container">
    <div class="contact">
      <h3 class="redeem">.redeem dance</h3>
      <div>
        <div class="auxiliary">
          <p class="mail">mail@redeem.org</p>
          <p class="number">+233256547645</p>
          <address>3704 Hoffman Avenue, New York, NY 10016</address>
        </div>
      </div>
    </div>
    <div class="form-container">
      <h2>
        WANT TO <br />
        PRACTICE?
      </h2>
      <p>SIGN UP FOR A FREE PRACTICE SESSION</p>
      <form action="#">
        <div class="form-group">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required />
        </div>
        <div class="form-group">
          <label for="phone">Phone Number:</label>
          <input type="tel" id="phone" name="phone" required />
        </div>
        <div class="checkbox-group">
          <input type="checkbox" id="terms" name="terms" required />
          <label for="terms">I agree to the processing of personal data</label>
        </div>
        <button class="button" type="submit">Sign Up</button>
      </form>
    </div>
  </div>
</template>

<style>
/* body {
  font-family: sans-serif;
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f5f5f5;
} */
.contact-container {
  display: flex;
  width: 100%;
}
.contact {
  margin-left: 20%;
}
.second {
  margin-left: 15%;
  margin-top: 20%;
  font-size: 30px;
  word-spacing: 3px;
  letter-spacing: 2px;
}
.underline {
  border-bottom: 1px solid black; /* Define underline style */
  padding-bottom: 5px; /* Add space between text and underline */
}
.redeem {
  color: orangered;
  /* opacity: 0.5; */
  font-size: 2rem;
  letter-spacing: 3px;
}
.mail {
  color: red;

  font-size: 1.3rem;
}
.auxiliary {
  margin-left: 10%;
  opacity: 0.5;
}
.form-container {
  background-color: #ddd;

  /* padding-top: 130px;
  padding-bottom: 130px;
  padding-left: 30px;
  padding-right: 30px; */
  /* border-radius: 10px; */
  /* margin-left: 30%;
  margin-right: 10%; */
  /* box-shadow: 0 0 10px rgba(0, 0, 0, 0.2); */
  width: 650px; /* Adjust width as needed */
  max-width: 100%;
}

.form-container h2 {
  padding: 0px 10px;
  margin-left: 55px;
  font-size: 6rem;
  /* margin-bottom: 20px; */
}
.form-container p {
  padding-top: 0;
  text-align: center;
  opacity: 0.5;
  font-size: 1.6rem;
}

.form-group {
  margin-top: 0;
  margin-bottom: 15px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
}
input[type="text"],
input[type="tel"],
input[type="password"] {
  border: none; /* Remove default border */
  border-bottom: 1px solid black; /* Add bottom line */
  background-color: transparent; /* Remove background color */
  padding: 5px; /* Add some padding for usability */
  outline: none; /* Remove outline on focus */
  width: 100%; /* Make input field take full width */
  box-sizing: border-box; /* Include padding in width calculation */
}

input[type="text"]:focus,
input[type="tel"]:focus,
input[type="password"]:focus {
  border-bottom-color: red; /* Change line color to red on focus */
}

/* .form-group input {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  width: 100%;
  box-sizing: border-box;
} */
.form-group {
  margin-left: 80px;
}
.checkbox-group {
  margin-left: 80px;
  display: flex;
  align-items: center;
  margin-bottom: 15px;
}

.checkbox-group input[type="checkbox"] {
  margin-right: 10px;
}

.button {
  margin-left: 80px;
  margin-bottom: 40px;
  background-color: red;
  color: white;
  padding: 20px 30px;
  border: none;
  border-radius: 40px;
  cursor: pointer;
  transition: background-color 0.2s ease-in-out;
}

.button:hover {
  background-color: white;
  color: red;
  border: 1px solid red;
}
</style>
