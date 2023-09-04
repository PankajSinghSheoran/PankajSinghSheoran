<div class="container">
  <h1 align="center">Hi 👋, I'm Pankaj Singh Sheoran</h1>
  <h3 align="center">A passionate frontend developer from India</h3>
  <img align="right" alt="coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">
  <p align="left"> <img src="https://komarev.com/ghpvc/?username=pankajsinghsheoran&label=Profile views&color=0e75b6&style=flat" alt="pankajsinghsheoran" /> </p>
  <p align="left"> <a href="https://twitter.com/pankajs27091282" target="blank"><img src="https://img.shields.io/twitter/follow/pankajs27091282?logo=twitter&style=for-the-badge" alt="pankajs27091282" /></a> </p>
  <ul>
    <li>🔭 I’m currently working on React Projects</li>
    <li>🌱 I’m currently learning ReactJs, Typescript, Javascript, Tailwind CSS</li>
    <li>👯 I’m looking to collaborate on React Projects</li>
    <li>💬 Ask me about HTML, CSS, Javascript, Bootstrap</li>
    <li>📫 How to reach me: pankajsheoran728@gmail.com</li>
    <li>⚡ Fun fact: I am a procrastinator, but super focused on my work.</li>
  </ul>
  <h3 align="left">Connect with me:</h3>
  <p align="left">
    <a href="https://twitter.com/pankajs27091282" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="pankajs27091282" height="30" width="40" /></a>
    <a href="https://linkedin.com/in/pankaj singh sheoran" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="pankaj singh sheoran" height="30" width="40" /></a>
    <a href="https://fb.com/pankaj singh sheoran" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="pankaj singh sheoran" height="30" width="40" /></a>
    <a href="https://instagram.com/pankaj_singh_sheoran" target="_blank"><img align="center" src="<EUGPSCoordinates>" alt="<EUGPSCoordinates>" height="<EUGPSCoordinates>" width="<EUGPSCoordinates>" /></a>
  </p>
  <div class='snake-container'>
    <div class='snake'></div>
  </div>
</div>

<style>
.container {
  position: relative;
}

.snake-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.snake {
  position: absolute;
  top: -10px;
  left: -10px;
  width: 10px;
  height: 10px;
  background-color: green;
}

@keyframes move-snake {
  from { top: -10px; left: -10px; }
  to { top: calc(100% + 10px); left: calc(100% + 10px); }
}

.snake {
  animation-name: move-snake;
  animation-duration: 5s;
}
</style>

<script>
const snake = document.querySelector('.snake');
snake.addEventListener('animationend', () => {
   document.querySelector('.container').remove();
});
</script>
