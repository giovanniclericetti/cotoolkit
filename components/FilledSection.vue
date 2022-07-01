<template>

  <!--
    ORDINE CAMBIATO
    <b-col order="2" order-lg="10">TERZO</b-col> -->

  <div class="container-fluid filled justify-content-center p-5">

    <h2 class="my-4 mt-5">
      <slot/>
    </h2>

    <div class="row justify-content-center">
      <p class="subtitle ">
        {{ sottotitolo }}
      </p>

    </div>

    <div class="my-md-5">
      <ButtonFigma>
        Accedi al pack
      </ButtonFigma>
    </div>


  </div>

</template>

<script>

export default {
  name: 'FilledSection',
  props: ['title', 'imgSrc', 'chisono', 'sottotitolo'],



}

</script>

<style>

.filled {
  width: 100vw;
  text-align: center;
  color: white;
background-color: var(--color-primary);
}

.subtitle {
  max-width: 630px;
  color: white;
}


</style>
