<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      color: #333;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }
    .header, .section {
      background-color: #fff;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      margin-bottom: 20px;
      padding: 20px;
      border-radius: 8px;
    }
    .header h1, .header h3 {
      margin: 0;
      text-align: center;
    }
    .header img {
      display: block;
      margin: 20px auto;
    }
    .section h3 {
      margin-bottom: 10px;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .skill {
      width: 45%;
      margin-bottom: 10px;
    }
    .skill h4 {
      margin: 0 0 5px 0;
    }
    .skill-progress {
      background: #e0e0e0;
      border-radius: 5px;
      overflow: hidden;
    }
    .skill-progress div {
      height: 10px;
      background: #4caf50;
    }
    .connect img, .languages img {
      margin: 5px;
      transition: transform 0.3s;
    }
    .connect img:hover, .languages img:hover {
      transform: scale(1.1);
    }
    .slider {
      width: 100%;
      overflow: hidden;
      position: relative;
    }
    .slides {
      display: flex;
      transition: transform 0.5s ease-in-out;
    }
    .slides img {
      width: 100%;
      border-radius: 8px;
    }
    .slider-buttons {
      position: absolute;
      top: 50%;
      width: 100%;
      display: flex;
      justify-content: space-between;
      transform: translateY(-50%);
    }
    .slider-button {
      background-color: rgba(0, 0, 0, 0.5);
      border: none;
      color: white;
      padding: 10px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Hi 👋, I'm @Relaxkartikey</h1>
      <h3>A Student & Frontend Developer from India</h3>
      <img src="https://user-images.githubusercontent.com/34984526/126812572-fd218473-2f42-4c9d-81f8-59d7db3ae9a4.gif" alt="Coding" width="400" height="300"/>
    </div>
    <div class="section">
      <h3>About Me</h3>
      <p>🔭 I’m currently working on <b>Woocommerce and Frontend Projects</b></p>
      <p>🌱 I’m currently learning <b>Backend Frameworks based on Js</b></p>
      <p>👯 I’m looking to collaborate on <b>Open Source MERN</b></p>
      <p>💬 Ask me about <b>React, CSS, HTML5, Wordpress Org, Woocommerce</b></p>
      <p>📫 How to reach me <b>relaxkartikey@gmail.com</b></p>
    </div>
    <div class="section">
      <h3>Connect with me:</h3>
      <div class="connect">
        <a href="https://twitter.com/relaxkartikey" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30" width="40" />
        </a>
        <a href="https://linkedin.com/in/relaxkartikey" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
        </a>
        <a href="https://www.behance.net/relaxkartikey" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/behance.svg" alt="Behance" height="30" width="40" />
        </a>
      </div>
    </div>
    <div class="section">
      <h3>Languages and Tools:</h3>
      <div class="languages">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40"/>
        <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="40" height="40"/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40"/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="Photoshop" width="40" height="40"/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/>
      </div>
    </div>
    <div class="section">
      <h3>Skills:</h3>
      <div class="skills">
        <div class="skill">
          <h4>HTML</h4>
          <div class="skill-progress">
            <div style="width: 90%;"></div>
          </div>
        </div>
        <div class="skill">
          <h4>CSS</h4>
          <div class="skill-progress">
            <div style="width: 85%;"></div>
          </div>
        </div>
        <div class="skill">
          <h4>JavaScript</h4>
          <div class="skill-progress">
            <div style="width: 80%;"></div>
          </div>
        </div>
        <div class="skill">
          <h4>React</h4>
          <div class="skill-progress">
            <div style="width: 75%;"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <h3>Portfolio</h3>
      <div class="slider">
        <div class="slides">
          <img src="https://via.placeholder.com/900x400?text=Project+1" alt="Project 1">
          <img src="https://via.placeholder.com/900x400?text=Project+2" alt="Project 2">
          <img src="https://via.placeholder.com/900x400?text=Project+3" alt="Project 3">
        </div>
        <div class="slider-buttons">
          <button class="slider-button" onclick="prevSlide()">&#10094;</button>
          <button class="slider-button" onclick="nextSlide()">&#10095;</button>
        </div>
      </div>
    </div>
  </div>

  <script>
    let slideIndex = 0;
    showSlides();

    function showSlides() {
      let slides = document.querySelectorAll('.slides img');
      for (let i = 0; i < slides.length; i++) {
        slides[i].style.display = 'none';
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}
      slides[slideIndex-1].style.display = 'block';
      setTimeout(showSlides, 2000); // Change image every 2 seconds
    }

    function nextSlide() {
      slideIndex++;
      showSlides();
    }

    function prevSlide() {
      slideIndex--;
      showSlides();
    }
  </script>
</body>
</html>
