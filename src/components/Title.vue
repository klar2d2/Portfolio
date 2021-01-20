<template>
  <div class="hello">
    <h1 class="name">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "Title",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss'>
@import 'src/assets/sass/style.scss';

  .hello {
    height: 100vh;
    width: 100%;
    background-color: $color-main;
    color: $color-white;
  }

  .name {
    position: relative;
    top: 30%;
    font-size: 10rem;
  }
</style>
