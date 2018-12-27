<template>
  <div class="container">
    <div class="row">
      <div class="column 16 s12">
        <div class="carousel">
          <a class="carousel-item" href="#one!">
            <img src="../assets/Images/13916649992_845aed35a3_b.jpg">
          </a>
          <a class="carousel-item" href="#two!">
            <img src="../assets/Images/24503467270_4781335b0d_b.jpg">
          </a>
          <a class="carousel-item" href="#three!">
            <img src="../assets/Images/GXTWb44p_QWosuvk4EJxomNbU5Sf5Opn1ZxUlVRVKGY.jpg">
          </a>
          <a class="carousel-item" href="#four!">
            <img src="../assets/Images/Petrova_Julian612.jpg">
          </a>
          <a class="carousel-item" href="#five!">
            <img src="../assets/Images/stock-photo-6820414.jpg">
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "PhotoBucket",
  props: {
    msg: String
  },
  events: {}
};
</script>
<style>
.example-slide {
  align-items: center;
  background-color: #666;
  color: #999;
  display: flex;
  font-size: 1.5rem;
  justify-content: center;
  min-height: 10rem;
}
</style>

 