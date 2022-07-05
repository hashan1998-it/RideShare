<!-- This is the navigation bar of the page -->

<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light navbar-custom container">
      <a class="navbar-brand" href="#">Navbar</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link nav-item_home" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link nav-item_added" href="#">How it works</a>
          </li>
          <li class="nav-item">
            <a class="nav-link nav-item_added" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link nav-item_added" href="#">Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link download-nav-button" href="#">Download</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {}
</script>

<style>
.nav-item_added {
  color: #d5ded4 !important;
}
.nav-item_added:hover {
  color: #fff !important;
}
.nav-item_home {
  color: #fff !important;
  font-weight: 600;
}
.nav-item_home:hover {
  text-shadow: 5px 5px 20px #fff, 5px 5px 20px #ccc;
}

.navbar-brand {
  color: #fff !important;
  font-weight: 700;
}
.navbar-custom{
  height: 10vh;
}

@media screen and (max-width: 768px) {
}
@media screen and (min-width: 768px) {
}
@media screen and (min-width: 1200px) {
}
@media screen and (min-width: 992px) {
  .download-nav-button {
    margin-left: 32px;
    border: 1px solid #44cb15;
    padding: 10px 20px !important;
    background: #44cb15;
    color: #fff !important;
    font-weight: 600;
    transition: 0.2s ease-in;
  }
  .download-nav-button:hover {
    box-shadow: inset 0 0 50px #44cb15, inset 20px 0 80px #44cb15,
      inset -20px 0 80px #44cb15, inset 20px 0 300px #44cb15,
      inset -20px 0 300px #44cb15, 0 0 50px #44cb15, -10px 0 80px #44cb15,
      10px 0 80px #44cb15;
  }
  .nav-item_added,
  .nav-item_home {
    margin-right: 20px !important;
  }
  nav {
    border-bottom: 1px solid #fff;
  }
}
</style>
