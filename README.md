# Hi 👋, I'm Pankaj Singh Sheoran

### A passionate frontend developer from India

!coding

!

!Twitter Follow

- 🔭 I’m currently working on React Projects
- 🌱 I’m currently learning ReactJs, Typescript, Javascript, Tailwind CSS
- 👯 I’m looking to collaborate on React Projects
- 💬 Ask me about HTML, CSS, Javascript, Bootstrap
- 📫 How to reach me: pankajsheoran728@gmail.com
- ⚡ Fun fact: I am a procrastinator, but super focused on my work.

### Connect with me:

<img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="pankajs27091282" height="30" width="40" />
<img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="pankaj singh sheoran" height="30" width="40" />
<img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="pankaj singh sheoran" height="30" width="40" />
<img align="center" src="<EUGPSCoordinates>" alt="<EUGPSCoordinates>" height="<EUGPSCoordinates>" width="<EUGPSCoordinates>" />

<div class='snake-container'>
  <div class='snake'></div>
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
