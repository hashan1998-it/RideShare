<!-- This is the social media pane in the landing page -->
<template>
  <div class="social-media-pane d-flex flex-column justify-content-lg-center align-items-center">
    <a href="#"><img src="~/static/facebook.png" alt="facebook" /></a>
    <a href="#"><img src="~/static/twitter.png" alt="facebook" /></a>
    <a href="#"><img src="~/static/youtube.png" alt="facebook" /></a>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@media screen and (min-width: 992px) {
  .social-media-pane {
    width: 6vw;
    border-right: 1px solid #fff;
    height: 80vh;
    position: absolute;
  }
  img {
    width: 40px;
    height: 40px;
    margin-bottom: 30px;
  }
}

@media screen and (max-width: 992px) {
  .social-media-pane,
  img {
    display: none;
  }
}
</style>
