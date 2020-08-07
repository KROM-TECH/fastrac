<template>
  <div class="card">
    <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="30"
  >
    <b-carousel-slide
      caption="First slide"
      img-src="https://picsum.photos/1024/480/?image=10"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Second Slide"
      img-src="https://picsum.photos/1024/480/?image=12"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://picsum.photos/1024/480/?image=22"
    ></b-carousel-slide>
  </b-carousel>
</div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .card {
    width:100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: fit-content;
    margin-top: 30px;
    background-color: rgb(240, 240, 240);
    box-shadow: rgba(0, 0, 0, 0.07) 15px 15px 30px 0px, rgba(255, 255, 255, 0.8) -15px -15px 30px 0px;
    /* border-radius: 30px; */
    padding: 5px;
  }
</style>