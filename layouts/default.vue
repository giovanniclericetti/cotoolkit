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
    font-weight: 600;
    font-size: 73px;
  }

  h3{
    font-family: 'IBM Plex Sans';
    font-weight: 600;
    font-size: 32px;
  }

  h4{
    font-family: 'IBM Plex Sans';
    font-weight: 400;
    font-size: 25px;
    color: #7D7D7D;
  }

  p{
    font-size: 20px;
  }

  .subtitle{
    color: #7D7D7D;
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
