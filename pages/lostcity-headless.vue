<template>
  <div>
    <div class="ing-content nes-container">
      <div class="nes-container is-dark with-title">
        <p class="title">
          LostCity Headless
        </p>
        <p>
          <img
            src="/lostcity-headless-console.png"
            alt="LostCity Headless console showing connected accounts and game activity"
            class="ing-600img"
          />
          <br>
          <br>
          LostCity Headless is a C++20 game client for LostCity-based RuneScape private servers.
          It maintains game state directly from server packets and runs Python bot scripts
          without rendering a game window.
          <br><br>
          The client runs on Windows and Linux, supports three protocol revisions, and handles
          up to 16 accounts per process. Asynchronous networking supports TCP, WebSocket and
          secure WebSocket connections, with optional SOCKS5 proxies.
          <br><br>
          Game cache data supplies item and NPC definitions, scenery and collision maps.
          Collision-aware pathfinding and world navigation let scripts move around the game
          and interact with its objects.
          <br><br>
          I embedded Python using pocketpy, giving each account its own interpreter and script.
          Development tools include live script reloading, VS Code debugging, performance
          profiling and editor type stubs.
          <br><br>
          <br>
          <a href="https://github.com/ineedbots/lc-headless">GitHub</a>
          <br>
          <a href="https://github.com/ineedbots/lc-headless/releases">Downloads</a>
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
      title: 'LostCity Headless',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'A C++20 headless client for LostCity-based RuneScape private servers, with Python bot scripting and collision-aware navigation.',
        },
      ],
    };
  },
};
</script>
