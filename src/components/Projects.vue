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
    alt: String
  }
};
</script>
