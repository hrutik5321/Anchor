<template>
  <div
    id="carouselExampleControls"
    class="carousel slide"
    data-bs-ride="carousel"
  >
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://ahadsohail.com/Mentor%20Ocean/sub%20pages/Gig%20Page/img/Profile%20Pic.png"
          class="d-block w-100 img-fluid"
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://ahadsohail.com/Mentor%20Ocean/sub%20pages/Gig%20Page/img/Profile%20Pic.png"
          class="d-block w-100"
        />
      </div>
      <div class="carousel-item">
        <img
          src="https://ahadsohail.com/Mentor%20Ocean/sub%20pages/Gig%20Page/img/Profile%20Pic.png"
          class="d-block w-100"
        />
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleControls"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleControls"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.img-fluid {
  width: 300px;
  height: 300px;
}
</style>
