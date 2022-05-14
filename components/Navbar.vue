<template>


  <nav class="navbar fixed-top navbar-expand-md navbar-light bg-white shadow">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <a class="navbar-brand px-5" href="#">
        <img src="~assets/svg/logo.svg" alt=""  height="40px" class="d-inline-block align-text-top ">
      </a>

  <div class="d-flex">
      <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
        <ul class="d-flex navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item px-5">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item px-5">
            <NuxtLink class="nav-link" to="/about"
            >About</NuxtLink
            >
          </li>
          <li class="nav-item px-5">
            <a class="nav-link">Risorse</a>
          </li>
        </ul>
      </div>
      </div>
    </div>
  </nav>

</template>

<script>

</script>

<style>

.shadow {
  filter: drop-shadow(0px 0px 0px rgba(10, 10, 10, 0.01));
}

</style>
