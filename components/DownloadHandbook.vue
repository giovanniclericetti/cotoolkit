<template>

  <!--
    ORDINE CAMBIATO
    <b-col order="2" order-lg="10">TERZO</b-col> -->

  <div class="container-fluid filled justify-content-center p-5">

    <h2 class="my-md-4 mt-md-5 testifilled">
      <slot/>
    </h2>

    <div class="row justify-content-center">
      <p class="subtitle ">
        {{ sottotitolo }}
      </p>

    </div>

    <div class="my-md-5">
      <a download target="_blank" href="/pdf/handbook.pdf"> <button type="button" class="btn  buttondownload d-inline-flex">

        <img class="iconfigma ps-3 pt-md-1 " src="~assets/images/download.png">

        <p class="px-3">
          Download
        </p>
      </button>  </a>
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

.buttondownload {
  background-color: white;
  border-radius: 15px;
  height: 42px;
}

.buttondownload:hover {
  background-color: #FCBB16;
  transition: 0.3s ease-in-out;
}

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

@media (max-width: 768px) {
.testifilled{
font-size: 35px;
}}


</style>
