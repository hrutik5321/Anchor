<template>
  <div class="container-fluid">
    <div class="top__header bg-dark d-flex justify-content-end">
      <div class="right__navigation">
        <a href="#">Home</a>
        <a href="#">Help</a>
        <a href="#">Teach</a>
        <a href="#">Login</a>
        <button class="btn btn-primary">Join for Free</button>
      </div>
    </div>
    <div class="sujession__bar p-2 d-flex justify-content-between">
      <a href="#">Graphic And Design</a>
      <a href="#">Digital Marketing</a>
      <a href="#">Music And Video</a>
      <a href="#">Writing and Translation</a>
      <a href="#">Music and Videos</a>
      <a href="#">Programming</a>
      <a href="#">Tech</a>
    </div>
    <hr />
    <div
      class="search__bar p-1 d-flex align-items-center justify-content-between"
    >
      <div class="search__bar--left">
        <a href="#">Overview</a>
        <a href="#">Description</a>
        <a href="#">About the Seller</a>
        <a href="#">Compare Packages</a>
        <a href="#">Reviews</a>
      </div>
      <div class="search__bar--center">
        <i class="fas fa-search"></i>
        <input
          type="text"
          placeholder="Hellow There"
          class="search__bar--input"
        />
        <button class="search__bar--btn">Search</button>
      </div>
      <div class="search__bar--right">
        <div class="dropdown">
          <button
            class="btn btn-secondary dropdown-toggle"
            type="button"
            id="dropdownMenu2"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            Dropdown
          </button>
          <ul class="dropdown-menu" aria-labelledby="dropdownMenu2">
            <li><button class="dropdown-item" type="button">Action</button></li>
            <li>
              <button class="dropdown-item" type="button">
                Another action
              </button>
            </li>
            <li>
              <button class="dropdown-item" type="button">
                Something else here
              </button>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <hr />
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.container-fluid {
  padding: 0;
}
.top__header {
  padding: 0.75rem 0 0.75rem 0 !important;
}
hr {
  margin: 0;
  padding: 0;
}
.right__navigation {
  margin-right: 65px;
}
.right__navigation > a {
  text-decoration: none;
  color: white;
  margin-right: 25px;
}
.sujession__bar {
  margin-left: 4.5rem;
  /* border-bottom: 1px solid #62646a; */
}
.sujession__bar > a {
  text-decoration: none;
  color: #62646a;
  margin-right: 2rem;
  font-size: 18px;
}
/* SEARCH BAR */
.search__bar {
  background-color: rgb(218, 218, 218);
  &--left > a {
    margin-left: 45px;
    text-decoration: none;
    color: #62646a;
    &:not(:first-child) {
      margin-left: 1rem;
    }
  }
  &--center {
    background-color: white;
    margin-left: 1.5rem;
    // border: 1px solid darkgray;
    padding: 5px 5px 5px 10px;
    display: flex;
    align-items: center;
    border-radius: 10px;
    & > i {
      color: #62646a;
      font-size: 16px;
      margin-bottom: -3px;
    }
  }
  &--input {
    border: none;
    padding: 4px;
    outline: none;
  }
  &--btn {
    background-color: greenyellow;
    color: white;
    padding: 5px 10px 5px 10px;
    border-radius: 5px;
    font-weight: bold;
    border: none;
    outline: none;
  }
}
</style>
