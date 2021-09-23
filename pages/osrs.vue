<template>
  <div>
    <div class="ing-content nes-container">
      <div class="nes-container is-dark with-title">
        <p class="title">
          ineedbot's OSRS Scripts
        </p>
        <p>
          <img src="/osrs.png" alt="OSRS" class="ing-600img"/>
          <br>
          <br>
          These were a collection of automation scripts for
          <a href="https://oldschool.runescape.com/">OldSchool RuneScape</a>.
          <br><br>
          It used an IDE known as <a href="https://villavu.com/forum/">Simba</a>.
          <br><br>
          Some of my scripts used a library that utilized <a href="https://github.com/KyleHunter/OSR-Reflection">java reflection</a>
          to read data from directly from the game client.
          This required maintenance to the library every time there was a game update.
          <br><br>
          Another set of my scripts used a library that used
          <a href="https://github.com/ollydev/SRL-Development">colour and AI</a>
          to detect the game's state. The advantage to this approach is that maintenance
          is only required if the game's visuals changes, which doesn't happen often.
          <br><br>
          <br>
          <a href="https://github.com/ineedbots/srl-osr-scripts">GitHub (color)</a> (maintained)
          <br>
          <a href="https://github.com/ineedbots/Scripts">GitHub (reflection)</a> (archived)
          <br>
          <a href="https://villavu.com/forum/showthread.php?t=100300">Forum post</a>
        </p>
      </div>

      <div style="height: 40px" />

      <NuxtLink to="/">
        Go back perhaps?
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'OSRS',
    };
  },
};
</script>
