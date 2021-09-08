<template>
  <div class="ing-root-div">
    <div class="container">
      <div class="top-bar ing-title">
        <span>INeedGames</span>
      </div>

      <Nuxt />

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

<script>
import '@fontsource/press-start-2p';
import 'nes.css/css/nes-core.min.css';
import 'bootstrap/dist/css/bootstrap.min.css';

export default {};
</script>

<style>
* {
  border-radius: 0px;
  font-family: "Press Start 2P";
}

html {
  cursor: default;
  background-color: #121212;
}

a, button {
  cursor: pointer;
}

.ing-root-div {
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

.ing-content {
    background-color: #1E1E1E;
    border-color: currentcolor;
    color: white;
}

li::before {
  color: rgb(17, 19, 141) !important
}
</style>
