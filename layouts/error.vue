<template>
  <div>
    <div class="ing-content nes-container">
      <h1 v-if="error.statusCode === 404">
        {{ pageNotFound }}
      </h1>
      <h1 v-else>
        {{ otherError }}
      </h1>
      <NuxtLink to="/">
        Go back perhaps?
      </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'empty',
  props: {
    error: {
      type: Object,
      default: null,
    },
  },
  data() {
    return {
      pageNotFound: 'Lost?',
      otherError: 'How did this happen??',
    };
  },
  head() {
    const title = this.error.statusCode === 404 ? this.pageNotFound : this.otherError;
    return {
      title,
    };
  },
};
</script>

<style scoped>
h1 {
  font-size: 30px;
}
* {
  text-align: center;
}
</style>
