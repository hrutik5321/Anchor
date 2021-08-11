<template>
  <TopBar />
  <GigView />
</template>

<script>
import GigView from "./components/GigView/GigView.vue";
import TopBar from "./components/TopBar/TopBar.vue";
export default {
  components: {
    TopBar,
    GigView,
  },
};
</script>

<style lang="scss"></style>
