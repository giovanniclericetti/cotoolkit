<template>
  <b-navbar toggleable="lg" type="light" class="navbar navbar-expand-sm  fixed-top navbar-expand-md navbar-light bg-white shadow">

    <b-navbar-toggle class="ml-auto togglenav px-4" target="nav-collapse" style="border: none;"></b-navbar-toggle>


    <b-navbar-brand class="navbar-brand px-3 px-md-5" to="/">

      <div class="desktop">
      <img src="~assets/svg/logo.svg" height="40px" class="d-inline-block align-text-top"></div>
     <div class="mobile p-0 m-0"> <img src="~assets/svg/logoreduction.svg"  height="40px" class="d-inline-block align-text-top p-1"> </div>
    </b-navbar-brand>


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
