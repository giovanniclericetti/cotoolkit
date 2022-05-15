
<template>
  <b-navbar toggleable="lg" type="light" class="navbar fixed-top navbar-expand-md navbar-light bg-white shadow">
    <b-navbar-brand href="#">

      <a class="navbar-brand px-5" href="#">
        <img src="~assets/svg/logo.svg" alt=""  height="40px" class="d-inline-block align-text-top ">
      </a>

    </b-navbar-brand>

    <b-navbar-toggle class="ml-auto" target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav class="right ml-auto justify-content-end">
      <b-navbar-nav>
        <b-nav-item href="#" class="px-4">Home</b-nav-item>
        <b-nav-item href="/about" class="px-4">About</b-nav-item>
        <b-nav-item href="#" class="px-4">Risorse</b-nav-item>

      </b-navbar-nav>
    </b-collapse>


  </b-navbar>
</template>


<script>

</script>

<style>

.shadow {
  filter: drop-shadow(0px 0px 0px rgba(10, 10, 10, 0.01));
}

</style>
