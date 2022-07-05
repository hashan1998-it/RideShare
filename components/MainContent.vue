<template>
  <div class="main-content">
    <div class="left-section">
      <HeaderText />
      <p class="content-para">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui culpa
        quia, voluptatibus pariatur id sequi dolorem fuga earum veniam nobis,
        nisi assumenda illo sunt soluta eligendi aspernatur beatae quae unde.
      </p>
      <GetItButton />
      <h6 class="lineadded-text py-2">OR</h6>
      <div class="getit-buttons d-flex align-items-lg-center">
        <img
          src="~/static/google.svg"
          alt="google"
          class="img-fluid google-img"
        />
        <img
          src="~/static/apple.svg"
          alt="google"
          class="img-fluid google-img"
        />
      </div>
    </div>
    <div class="right-section">
      <img
        src="~/static/mockup.png"
        alt="mockup"
        class="img-fluid mockup-img"
      />
    </div>
  </div>
</template>

<script>
import HeaderText from './HeaderText.vue'
import GetItButton from './GetItButton.vue'
export default {
  components: { HeaderText, GetItButton },
}
</script>

<style>
.main-content {
  height: 90vh;
  width: 94vw;
  position: absolute;
  right: 0;
  display: flex;
  overflow: hidden;
  z-index: 10;
}
.left-section,
.right-section {
  width: 50%;
  height: 90vh;
}
.content-para {
  padding: 5% 15%;
  font-family: Futura, Trebuchet MS, Arial, sans-serif;
  color: #f6f6f3;
  font-weight: 200;
}

@media screen and (max-width: 768px) {
  .main-content {
    width: 100vw;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .left-section,
  .right-section {
    width: 100%;
  }
  .left-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
}
@media screen and (min-width: 768px) {
  .main-content {
    width: 100vw;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .left-section,
  .right-section {
    width: 100%;
  }
  .left-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
}
@media screen and (min-width: 992px) {
  .main-content {
    width: 94vw;
    flex-direction: row;
  }
  .left-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  .mockup-img {
    width: 300px;
  }

  .right-section {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .google-img {
    width: 200px;
    height: 45px;
  }
  .lineadded-text{
    color: #fff;
  }
}
</style>
