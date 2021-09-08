<template>
  <div>
    <div class="ing-content nes-container">
      <div class="nes-container is-dark with-title">
        <p class="title">
          Bot Warfare
        </p>
        <p>
          <img src="/bwlogo.png" alt="Bot Warfare" style=""/>
          <br>
          <br>
          Bot Warfare is a GSC mod for various Call of Duty games that aims to add/enhance
          playable AI to multiplayer matches.
          <br><br>
          GSC is a scripting language that Call of Duty uses, and often Bot Warfare will make
          use of custom syscalls that were added to various Call of Duty modifications/clients,
          such as <a href="https://xlabs.dev/">IW4x</a> and
          <a href="https://plutonium.pw/">Plutonium</a>.
          <br><br>
          Bot Warfare uses AStar and a graph of points to allow the bots navigate and pathfind
          to their destinations.
          <br><br>
          <br>
          <a href="https://github.com/ineedbots/iw4x_bot_warfare">GitHub</a>
          <br>
          <a href="https://www.moddb.com/mods/bot-warfare">ModDB</a>
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
      title: 'Bot Warfare',
    };
  },
};
</script>
