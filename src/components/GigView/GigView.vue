<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-8">
        <GigLeft />
        <GigLeft />
        <GigLeft />
        <GigLeft />
        <GigLeft />
        <GigLeft />
        <GigLeft />
        <GigLeft />
        <GigLeft />
      </div>
      <div class="col-4 sticky-top">
        <GigRight />
      </div>
    </div>
  </div>
</template>

<script>
import GigLeft from "./GigLeft.vue";
import GigRight from "./GigRight.vue";
export default {
  components: { GigLeft, GigRight },
};
</script>

<style lang="scss" scoped></style>
