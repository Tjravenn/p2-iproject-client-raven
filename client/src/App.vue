<script>
import NavBar from "./components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>

<template>
  <div>
    <NavBar />
    <RouterView />
  </div>
</template>

<style></style>
