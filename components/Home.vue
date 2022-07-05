<!-- This is the Landing page of the page -->
<template>
  <div class="landing-page">
    <NavBar />
    <SocialBar />
    <MainContent/>
    <img src="~/static/wavesOpacity1.svg" alt="wave" class="wave-img">
  </div>
</template>

<script>
import NavBar from './NavBar.vue'
import SocialBar from './SocialBar.vue'
import MainContent from './MainContent.vue'
export default {
  name: 'Home',
  components: { NavBar, SocialBar, MainContent },
}
</script>

<style scoped>
.landing-page {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  width: 100%;
  height: 100vh;
  background: #134e5e; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to left,
    #71b280,
    #134e5e
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to left,
    #71b280,
    #134e5e
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
.wave-img{
  position: absolute;
  bottom: 0;
  transform: rotate(180deg);

}
</style>
