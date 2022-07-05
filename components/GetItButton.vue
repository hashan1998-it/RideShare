<template>
  <a href="#">Explore</a>
</template>

<script>
export default {}
</script>

<style scoped>
a {
  border: 1px solid;
  padding: 15px 68px;
  background: rgba(59, 183, 143, 0.25);
  box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
  border-radius: 10px;
  border: 1px solid rgba(255, 255, 255, 0.18);
  color: #fff;
  text-decoration: none;
}
a:hover {
  box-shadow: inset 0 0 50px #3bb78f, inset 20px 0 80px #3bb78f,
    inset -20px 0 80px #3bb78f, inset 20px 0 300px #3bb78f,
    inset -20px 0 300px #3bb78f, 0 0 50px #3bb78f, -10px 0 80px #3bb78f,
    10px 0 80px #3bb78f;
}
@media screen and (min-width: 992px) {
  a {
    text-decoration: none;
  }
}
</style>
