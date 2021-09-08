<template>
  <div class="root-div">
    <div class="container">
      <div class="top-bar">
        <span class="ing-title">INeedGames</span>
      </div>

      <div class="ing-content nes-container">
        <p>
          <img src="l3wcb.png" alt="Level 3 Woodcutting bot" />
          About me blaioaw haw 9d7awd akwdj a awidjawoidj aiod hawdio hd
        </p>

        <div style="height: 40px" />

        <div class="nes-container is-dark with-title">
          <p class="title">
            Projects
          </p>

          <div class="lists">
            <ul class="nes-list is-disc">
              <li>
                <NuxtLink to="/bot-warfare">Bot Warfare</NuxtLink>
              </li>
            </ul>
          </div>
        </div>

        <div style="height: 40px" />

        <div class="nes-container is-dark with-title">
          <p class="title">
            Links
          </p>
          <div class="lists">
            <ul class="nes-list is-disc">
              <li><a href="https://github.com/ineedbots">GitHub</a></li>
              <li>
                <a href="https://www.youtube.com/user/Yyhhggtt">YouTube</a>
              </li>
            </ul>
          </div>
        </div>

        <div style="height: 40px" />

        <span
          >Email:
          <a href="mailto:ineedbots@outlook.com">ineedbots@outlook.com</a></span
        >
      </div>

      <div class="ing-footer">
        <span
          >Theme via
          <a href="https://nostalgic-css.github.io/NES.css/">NES.css</a></span
        >
      </div>
    </div>

    <div class="fixed-bottom ing-footer">
      <span> - INeedGames/ineedbots (2009 and onwards)</span>
    </div>
  </div>
</template>

<style>
* {
  border-radius: 0px;
  font-family: "Press Start 2P";
}

html {
  cursor: default;
  background-color: #121212;
}

.root-div {
  background-color: #121212;
}

.ing-footer {
  background-color: #272727;
  color: white;
  padding: 6px 16px;
}

@keyframes ing-blackWhite {
  0% {
    color: white;
  }
  75% {
    color: black;
  }
}

.ing-title {
  font-size: 20px;
  padding: 5px;
  transition: color 1s;
  background-color: black;
  color: white;

  animation-name: ing-blackWhite;
  animation-iteration-count: infinite;
  animation-duration: 4s;
}
</style>

<script>
import '@fontsource/press-start-2p';
import 'nes.css/css/nes-core.min.css';
import 'bootstrap/dist/css/bootstrap.min.css';

export default {};
</script>
