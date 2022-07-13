<template>
  <b-navbar toggleable="lg" type="light" class="navbar fixed-top navbar-expand-md navbar-light bg-white shadow">
    <b-navbar-brand class="navbar-brand px-5" to="/">

      <img src="~assets/svg/logo.svg" alt="" height="40px" class="d-inline-block align-text-top ">

    </b-navbar-brand>

    <b-navbar-toggle class="ml-auto" target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav class="right ml-auto justify-content-end my">
      <b-navbar-nav>
        <b-nav-item to="/" class="px-4" exact active-class="active">Home</b-nav-item>
        <b-nav-item to="/about/" class="px-4" exact active-class="active">About</b-nav-item>
        <b-nav-item to="/risorse/" class="px-4" exact active-class="active">Risorse</b-nav-item>

      </b-navbar-nav>
    </b-collapse>


  </b-navbar>
</template>


<script>

</script>

<style>



</style>
