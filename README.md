<link rel="stylesheet" href="https://kit.fontawesome.com/b62766c4e7.css" crossorigin="anonymous">
@import url('https://fonts.googleapis.com/css2?family=Permanent+Marker&display=swap');

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
body {
  height: 100vh;
  width: 100%;
  font-family: "Permanent Marker", cursive;
  color: white;
  background-color: #000;
  background-image: url(images/mixkit-exhausted-man-in-front-of-a-computer-with-his-head-69-original.png);
  background-size: cover;
}
.shadow {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  background-color: rgba(0, 0, 0, 0.97);
  z-index: -1;
}
header {
  width: 100%;
  display: flex;
  justify-content: center;
  position: relative;
}
header::before {
  content: "";
  position: absolute;
  width: 80%;
  height: 3px;
  background-color: yellow;
  bottom: -10px;
}

h1 {
  width: 400px;
  text-align: center;
  text-shadow: 2px 2px 2px black, 2px 2px 1px white;
}
h1 span {
  color: yellow;
}
img {
  width: 50px;
}
.programmer {
  width: 400px;
  border-radius: 10px;
  border: 3px solid black;
  outline: 3px solid yellow;
  margin: 20px calc(50% - 200px);
}
.skills {
  height: max-content;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  font-size: 1.8rem;
  margin-top: 50px;
  width: 500px;
  margin: auto;
}
.skills ul {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  gap: 10px;
  margin: 0;
  height: 58px;
}
.skills li {
  border-radius: 8px;
  padding: 2px;
  background-color: black;
  border: 2px solid yellow;
  outline: 2px solid black;
  height: 100%;
}

.skills img {
  height: 50px;
}
a img {
  width: 30px;
}
ul {
  list-style: none;
}
.projects {
  margin: 50px auto;
  width: 80%;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.projects a {
  text-decoration: none;
  color: yellow;
  font-size: 12px;
}
.projects li {
  position: relative;
}
.projects li::before {
  font: var(--fa-font-brands);
  content: "\f113";
  position: absolute;
  left: -30px;
  top: 50%;
  transform: translateY(-50%);
  color: yellow;
}
footer {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: flex-start;
  position: absolute;
  left: 5px;
  top: 50%;
  transform: translateY(-50%);
}
footer li {
  transition: 0.5s linear;
}
footer li:hover {
  transform: scale(1.2);
}
footer img[alt="linkedin"]{
  width:50px}
<body>
<div class="shadow"></div>
    <header>
      <h1>I am <span>Anas Elkalla</span> Welcome to my profile</h1>
    </header>
    <main>
      <img
        class="programmer"
        src="images/giphy.gif"
        alt="programmer"
      />
    </main>
    <div class="skills">
      <span>Skills</span>
      <ul style="list-style:none">
        <li>
          <img
            src="images/html-5.png"
            alt="html"
          />
        </li>
        <li>
          <img
            src="images/css-3.png"
            alt="css"
          />
        </li>
        <li>
          <img
            src="images/js.png"
            alt="javascript"
          />
        </li>
      </ul>
    </div>
    <div class="projects">
      <div class="css">
        <span>CSS Projects</span>
        <ul style="list-style:none">
          <li>
            <a
              href="https://github.com/AnasElkalla/product-preview-card-component-main"
            >
              product card component</a
            >
          </li>
          <li>
            <a href="https://github.com/AnasElkalla/leon-template"
              >leon template</a
            >
          </li>
          <li>
            <a href="https://github.com/AnasElkalla/candle">Candle</a>
          </li>
          <li>
            <a href="https://github.com/AnasElkalla/rotatingEarthPlanet"
              >Rotating Planet Earth</a
            >
          </li>
        </ul>
      </div>
      <div class="js">
        <span>Javascript Projects</span>
        <ul style="list-style:none">
          <li>
            <a href="https://github.com/AnasElkalla/hammerURL">Hammer URL</a>
          </li>
          <li>
            <a href="https://github.com/AnasElkalla/border-radius-generator"
              >Border Radius Generator</a
            >
          </li>
          <li>
            <a href="https://github.com/AnasElkalla/Custom-Color-palette"
              >Custom Color palette
            </a>
          </li>
        </ul>
      </div>
    </div>
    <footer>
      <ul style="list-style:none">
        <li>
          <a href="https://www.linkedin.com/in/anas-elkalla-8b0432111/"
            ><img
              src="https://cdn-icons-png.flaticon.com/512/3536/3536505.png"
              alt="linkedin"
                  style="width:50px"
          /></a>
        </li>
        <li>
          <a href="https://codepen.io/anaselkalla"
            ><img
              src="https://cdn-icons-png.flaticon.com/512/1377/1377243.png"
              alt="codepen" style="width:50px"
          /></a>
        </li>
        <li>
          <a href="https://www.instagram.com/anas_elkalla/"
            ><img
              src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png"
              alt="instagram"  style="width:50px"
          /></a>
        </li>
        <li>
          <a href="https://twitter.com/anaselkala"
            ><img
              src="https://cdn-icons-png.flaticon.com/512/3256/3256013.png"
              alt="twitter"  style="width:50px"
          /></a>
        </li>
      </ul>
    </footer>
</body>
