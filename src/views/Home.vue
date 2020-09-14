<template>
  <div class="home">
    <Title msg="Kobe Ryan" />
    <Projects msg="Munch My Lawn" img="@/assets/logo.png" alt="logo"/>
    <Projects msg="Met Museum Organizer" />
    <Projects msg="Inkline" />
    <Projects msg="Shoe Lace Simulator" />
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
  }
};
</script>
