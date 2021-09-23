<template>
  <div>
    <div class="ing-content nes-container">
      <div class="nes-container is-dark with-title">
        <p class="title">
          CoD2M
        </p>
        <p>
          <img src="/cod2.png" alt="CoD2" class="ing-600img"/>
          <br>
          <br>
          CoD2M is a modification for the Windows video game
          <a href="https://store.steampowered.com/app/2630/Call_of_Duty_2/">Call of Duty 2</a>.
          <br><br>
          It builds into a D3D9 DLL proxy (thanks momo5502) that runs when the game starts up.
          It uses C++ and x86 assembly to perform the modifications to the game.
          <br><br>
          The main purpose of this project is to allow my
          <NuxtLink to="/bot-warfare">Bot Warfare</NuxtLink>
          mod to work with CoD2, but it also adds a lot of other features to the game.
          <br><br>
          <br>
          <a href="https://github.com/ineedbots/cod2m/">GitHub</a>
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
      title: 'CoD2M',
    };
  },
};
</script>
