<template>
  <div class="home" ref="loop">
    <Title msg="Kobe Ryan" class="first piece"/>
    <Projects class="piece" msg="Munch My Lawn" img="@/assets/logo.png" alt="logo"/>
    <Projects class="piece" msg="Met Museum Organizer" img="" alt="logo" />
    <Projects class="piece" msg="Inkline" img="" alt="logo" />
    <Projects class="piece" msg="Shoe Lace Simulator" img="" alt="logo" />
    <Title msg="Kobe Ryan" class="first piece" ref="clone"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Title from "@/components/Title.vue";
import Projects from "@/components/Projects.vue";

export default {
  name: "Home",
  components: {
    Title,
    Projects
  },
  methods: {},
  mounted: {

  }
};



</script>

<style lang='scss'>
@import 'src/assets/sass/style.scss';

  .home {
    overflow-x: scroll;
    overflow-y: hidden;
    white-space: nowrap;
    background-color: $color-white;
  }
  .first {
  }
  .piece {
    display: inline-block;
  }

</style>
