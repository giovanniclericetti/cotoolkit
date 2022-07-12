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

  .shadow {
    filter: drop-shadow(0px 0px 0px rgba(10, 10, 10, 0.01));
  }

  a{
    text-decoration: none;
    color: black;
  }

  svg .show-on-hover {
    opacity: 0;
  }

  svg {
    transition: 0.3s ease-in-out;
  }


  svg:hover{
    transform: scale(1.03);
  }

  svg:hover .show-on-hover {
    opacity: 1;
  }

  b-link {
    color: black;
    text-decoration: none;
  }

  :root {
    --color-primary: #FCBB16;
  }

  .theme-red {
    --color-primary: #EE1000;
  }

  .theme-yellow {
    --color-primary: #FCBB16;
  }

  .theme-green{
    --color-primary: #24B265;
  }

  .theme-purple{
    --color-primary: #9747FF;
  }

  .theme-blue{
    --color-primary: #4EAAF0;
  }




  .text-primary {
    color: var(--color-primary);
  }

  .cardhome{
    border: none;
    border-radius: 20px;
    background-color: #F9F9F9;
    height: 100%;

  }

  .tools{
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

  @media (max-width: 768px) {

    h2{

      font-size: 50px;
    }

    h3{

      font-size: 35px;
    }

    h4{

      font-size: 20px;
    }

    h5{

      font-size: 25px;
    }

    p{
      font-size:16px;
    }


  }
</style>
