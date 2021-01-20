<template>
  <div class="projects">
    <h1>{{msg}}</h1>
    <img :src="img" :alt="alt" />
  </div>
</template>

<script>

export default {
  name: "Projects",
  props: {
    msg: String,
    img: String,
    alt: String,
    link: String
  }
};
</script>

<style lang="scss">
@import 'src/assets/sass/style.scss';

  .projects {
    width: 100%;
    background-color: $color-white;
    color: $color-dark;
  }
</style>
