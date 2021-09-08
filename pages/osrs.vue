<template>
  <div>
    <div class="ing-content nes-container">
      <div class="nes-container is-dark with-title">
        <p class="title">
          ineedbot's OSRS Scripts
        </p>
        <p>
          <img src="/osrs.png" alt="OSRS" style=""/>
          <br>
          <br>
          These were a collection of automation scripts for
          <a href="https://oldschool.runescape.com/">OldSchool RuneScape</a>.
          <br><br>
          It used an IDE known as <a href="https://villavu.com/forum/">Simba</a>.
          <br><br>
          My scripts used a library that utilized <a href="https://github.com/KyleHunter/OSR-Reflection">java reflection</a>
          to read data from the game client.
          <br><br>
          <br>
          <a href="https://github.com/ineedbots/Scripts">GitHub</a> (archived)
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
