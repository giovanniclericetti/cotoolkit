<template>
  <main class="global-wrapper">
    <Nuxt />
  </main>
</template>

<style>

  .global-wrapper {
    margin: 0px;
    overflow: hidden;
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

.linkino {
    color: black;
  }

  :root {
    --color-primary: #FCBB16;
  }

  .theme-red {
    --color-primary: #F45A5D;
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

  .theme-grey{
    --color-primary: #7D7D7D;
  }

  .whiteicon {
    color: white !important;

  }




  .cardhome:hover #hoverimage {
    transform: scale(1.1);
    transition: 0.3s ease-in-out;
  }

  #hoverimage {
    transition: 0.3s ease-in-out;
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
    background-image: url("~assets/svg/card4.svg");
    background-size: 120%;
    transition: 0.3s ease-in-out;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }



  .boxhomebg:hover{
    background-size: 130%;
    transition: 0.3s ease-in-out;
  }



  .desktop{
    display: block;
  }

  .mobile{
    display: none;
  }

  .iconhover:hover{
    text-decoration: none;
    color: black;

  }

  .boxhomebg:hover{
    background-size: 130%;
    transition: 0.3s ease-in-out;
  }




  @media (max-width: 768px) {

    .desktop{
      display: none;
    }

    .mobile{
      display: block;
    }



    h2{

      font-size: 50px;
    }

    h3{

      font-size: 35px;
    }

    h4{

      font-size: 35px;
    }

    h5{

      font-size: 20px;
    }

    p{
      font-size:16px;
    }

    svg .show-on-hover {
      opacity: 1;
    }


  }
</style>
