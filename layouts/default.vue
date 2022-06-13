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
    font-size: 65px;
  }

  h3{
    font-family: 'IBM Plex Sans';
    font-weight: 600;
    font-size: 40px;
  }

  h4{
    font-family: 'IBM Plex Sans';
    font-weight: 600;
    font-size: 32px;
  }

  h5{
    font-family: 'IBM Plex Sans';
    font-weight: 400;
    font-size: 25px;
    color: #7D7D7D;
  }

  h7{
    font-size: 20px;
  }

  p{
    font-size: 20px;
  }

  .subtitle{
    color: #7D7D7D;
  }

  a{
    text-decoration: none;
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


  @media (max-width: 768px) {

    h2{

      font-size: 65px;
    }

    h3{

      font-size: 35px;
    }

    h4{

      font-size: 32px;
    }

    h5{

      font-size: 25px;
    }


  }
</style>
