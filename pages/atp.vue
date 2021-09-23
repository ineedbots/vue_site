<template>
  <div>
    <div class="ing-content nes-container">
      <div class="nes-container is-dark with-title">
        <p class="title">
          Air Traffic Pro
        </p>
        <p>
          <img src="/atp.png" alt="Air Traffic Pro" class="ing-600img"/>
          <br>
          <br>
          Air Traffic Pro was a modification for
          <a href="https://store.steampowered.com/app/12120/Grand_Theft_Auto_San_Andreas/">Grand Theft Auto: San Andreas</a>.
          <br><br>
          It used a plugin called <a href="http://cleo.li/">CLEO</a> which allowed modders to write scripts to change, add and interact with the game.
          <br><br>
          <br>
          <a href="https://www.gtagarage.com/mods/show.php?id=15225">GTAGarage</a>
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
      title: 'Air Traffic Pro',
    };
  },
};
</script>
