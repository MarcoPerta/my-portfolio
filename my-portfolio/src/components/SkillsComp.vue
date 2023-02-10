<template>
  <div id="skills">
    <div class="container">
      <h2 class="text-center">Skills</h2>
      <h3 class="text-center">Front-end</h3>
      <div class="row p-3">
        <div
          id="carouselExampleInterval"
          class="carousel slide"
          data-bs-ride="carousel"
        >
          <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="10000">
              <img
                src="../assets/loghi-front/HTML.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
            <div class="carousel-item" data-bs-interval="2000">
              <img
                src="../assets/loghi-front/CSS.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/loghi-front/JAVASCRIPT.png"
                class="d-block w-100"
                alt="..."
              />
            </div>

            <div class="carousel-item">
              <img
                src="../assets/loghi-front/VUE.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/loghi-front/Axios.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/loghi-front/JQUERY.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/loghi-front/Bootstrap.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/loghi-front/LARAVEL.png"
                class="d-block w-100"
                alt="..."
              />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleInterval"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleInterval"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
#skills {
  background-color: #9c9c9c;
}
.carousel{
    margin: auto !important;
    width: unset!important;
    max-width: unset!important;
    padding-right: unset!important;
    padding-left: unset!important;
    margin-top: unset!important;
}
.carousel-inner{
    width: 300px !important;
    height: 200px !important;
    border-radius: 10px 10px 10px 10px;
}
img {
  width: 100%;
  height: 100%;
}
</style>


#0A0C0C