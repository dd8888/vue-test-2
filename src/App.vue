<template>
  <div>
    <NorrisJoke type="chuck" />
    <NorrisJoke type="nicholas" />
  </div>
</template>

<script>
import NorrisJoke from "./components/NorrisJoke.vue";
export default {
  name: "App",
  components: {
    NorrisJoke
  },
  data() {
    return {
      title: "Me llamo Pepe"
    };
  }
};
</script>

<style></style>
