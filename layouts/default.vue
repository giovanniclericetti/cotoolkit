<template>
  <main class="global-wrapper">
    <Nuxt />
  </main>
</template>

<style>

  .global-wrapper {
    margin: 0px;
  }

  body{
    font-family: 'IBM Plex Sans';
  }

  h2{
    font-family: 'IBM Plex Sans';
    font-weight: 700;
    font-size: 55px;
  }

  p{
    font-size: 20px;
  }

  svg .show-on-hover {
    opacity: 0;
  }

  svg:hover .show-on-hover {
    opacity: 1;
    transition: 0.3s ease-in-out;
  }

  svg:hover{
  transform: scale(1.03);
    transition: 0.3s ease-in-out;}

</style>
