# Puthy-TouchSokhon
My_Portfolio

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />
    <link rel="stylesheet" href="Css_Portfolio.css">

    <title>Puthy TouchSokhon</title>
  </head>
<header>
  <a href="#" class="logo">Puthy</a>
  <body>
<nav>
  <a class="contact_tele" href="https://t.me/PUTHY_13" target="_blank" >
      Contact
</a>
    <a href="#" class="actives" target="_blank">Home</a>
    <!-- <a href="#">About</a> -->
    <!-- <a href="#">Contact</a> -->
    <a href="#">Educations</a>
    <label for="roles"></label>
    <select id="roles" name="roles" class="styled-select">
      <option value="RUPP(Major IT)">IT (RUPP)</option>
      <!-- <option value="BACII">C (BACII)</option>
      <option value="Spring Education Center">GEP 10</option> -->
    </select>
    <a href="#">Skills
      <label for="roles"></label>
<select id="roles" name="roles" class="styled-select">
  <option value="frontend">C,C++,HTML,CSS</option>
  <option value="Research">Research</option>
  <option value="Good Communication">Good Communication</option>
  <option value="Basketball">Basketball</option>
  <option value="Flexible">Flexible</option>
  <option value="Support User">Support User</option>
</select>
    </a>
    <!-- <a href="https://t.me/PUTHY_13" target="_blank" style="text-decoration: none;">
      <button 
      style="background-color: #0088cc; color: white; 
      padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer;">
          Contact on Telegram
      </button>
  </a> -->
</nav>
</header>
<section class="home">
    <div class="home_img">
        <img src="Puthy-removebg-preview.png" alt="Image1">
    </div>
    <div class="home_content">
        <h1>Hi I'm Puthy <span></span></h1>
        <h3 class="typing_text"> I'm a<span></span></h3>
        <p>I am a flexible, reliable, self-motivated, and
          hardworking college student seeking
          employment. Adept at working
          independently and collaboratively on
          projects, and committed to achieving
          visual innovation</p>
    <div class="social_icon">
        <a href="https://www.facebook.com/touchsokhon.puthy?mibextid=LQQJ4d" target="_blank"><i class="fab fa-facebook"></i></a>
        <a href="https://www.tiktok.com/@puthy1306?is_from_webapp=1&sender_device=pc" target="_blank"><i class="fab fa-tiktok"></i></a>
        <a href="https://www.instagram.com/puthyyy_thyy_thy/profilecard" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://t.me/PUTHY_13" target="_blank"><i class="fab fa-telegram"></i></a>
    </div>
<div  class="btn">
    <!-- Hire Me!! -->
    <a href="https://www.canva.com/design/DAGUdoPqWpE/V5SYNQa2NZkJq7D-XUf5yw/view?utm_content=DAGUdoPqWpE&utm_campaign=designshare&utm_medium=link&utm_source=editor" target="_blank"> Hire Me!!</a>
</div>
    </div>
</section>
  </body>
</html>

/* Import Google Fonts */
@import url(https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600&display=swap);

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  border: none;
  outline: none;
  font-family: "Poppins", "Helvetica Neue";
}

html {
  font-size: 63%;
}

body {
  width: 100%;
  height: 100vh;
  overflow-x: hidden;
  background-color: black;
  color: white;
}

header {
  margin-top: 20px;
  position: relative;
  left: 0;
  top: 0;
  width: 100%;
  padding: 1rem 9%;
  background-color: transparent;
  filter: drop-shadow(10px);
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 100;
}

.logo {
  font-size: 2.5rem;
  cursor: pointer;
  font-weight: 800;
  color: red;
  transition: all 0.5s ease;
}

.logo:hover {
  color: rgb(0, 109, 128);
  transform: scale(1.1);
}
/* .contact_tele {
  font-size: 1.8rem;
  color: white;
  margin-left: 4rem;
  font-weight: 500;
  transition: all 0.3s ease;
  border-bottom: 3px solid transparent;
  display: block;
} */
nav a {
  font-size: 1.8rem;
  color: white;
  margin-left: 4rem;
  font-weight: 500;
  transition: all 0.3s ease;
  border-bottom: 3px solid transparent;
}
nav a:hover,
nav a:active {
  border-bottom: 3px solid white;
}
@media (max-width: 767px) {
  nav {
    position: absolute;
    top: 0;
    right: 0;
    width: 40%;
    border-left: 3px solid white;
    background-color: black;
    padding: 1rem;
  }
}

nav.active {
  display: block;
}

section {
  min-height: 100vh;
  padding: 2rem 10%;
}

.home {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  gap: 8rem;
  background-color: rgb(18, 164, 212);
}

.home .home_content h1 {
  font-size: 6rem;
  font-weight: 700;
  line-height: 1.3;
}

span {
  color: red;
}

.home_content h3 {
  font-size: 4rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

.home_img {
  border-radius: 50%;
}

.home_img img {
  width: 32vw;
  border-radius: 50%;
  box-shadow: 0 0 25px rgb(0, 162, 255);
  cursor: pointer;
  transition: all 0.2s linear;
}

.home_img img:hover {
  transform: scale(1.05);
  box-shadow: 0 0 30px rgb(243, 228, 228);
}

.social_icon a {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 4rem;
  height: 4rem;
  background-color: transparent;
  border: 0.2rem solid red;
  font-size: 2rem;
  border-radius: 50%;
  margin: 3rem 1.5rem;
  transition: all 0.3s ease;
}

.social_icon a:hover {
  color: black;
  transform: scale(1.3) translateY(-5px);
  background-color: red;
  box-shadow: 0 0 25px red;
}

.btn {
  display: inline-block;
  padding: 1rem 2rem;
  background-color: rgb(18, 164, 212);
  border-radius: 4rem;
  font-size: 1.6rem;
  color: red;
  letter-spacing: 0.2rem;
  font-weight: 600;
  border: 2px solid rgb(240, 19, 19);
  cursor: pointer;
  transition: all 0.3s ease;
}

.btn:hover {
  transform: scale(1.03);
  background-color: rgb(229, 221, 229);
  color: rgb(228, 11, 11);
  box-shadow: 0 0 10px rgb(12, 122, 190);
}

.typing_text {
  font-size: 30px;
  font-weight: 600;
  min-width: 280px;
}

.typing_text span {
  position: relative;
}

.typing_text span::before {
  content: " IT Support.";
  color: rgb(208, 72, 72);
  animation: words 5s infinite;
}

.typing_text span::after {
  /* content: "Frontend Developer"; */
  background-color: rgb(18, 159, 206);
  position: absolute;
  height: 100%;
  width: calc(100% + 8px);
  border-left: 3px solid rgb(13, 201, 185);
  right: -8px;
  animation: cursor 0.6s infinite;
  font-size: 40px;
}

@keyframes cursor {
  to {
    border-left: 3px solid rgb(233, 22, 22);
  }
}
@keyframes words {
  0%,
  25% {
    content: " Software Developer";
  }
  26%,
  50% {
    content: " Cyber Security";
  }
  51%,
  70% {
    content: " Graphics Design";
  }
  71%,
  100% {
    content: " IT Support";
  }
}
@media (max-width: 1000px) {
  .home {
    gap: 4rem;
  }
}

@media (max-width: 995px) {
  .home {
    flex-direction: column;
    margin: 5rem 4rem;
  }
  .home .home-content h3 {
    font-size: 2.5rem;
  }
  .home_img img {
    margin-top: 4rem;
  }
}
