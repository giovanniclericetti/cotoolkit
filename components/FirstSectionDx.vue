<template>

  <div class="container-fluid sectionone mt-5 px-5">



    <div class="row align-items-center px-5">
      <div class="col">

        <img class="gifcover" src="~assets/images/risorse.gif">

      </div>

      <div class="col-md-6 rightsubtitle">

        <h2 class="mb-4 ">
          <slot/>
        </h2>



        <h5 class="text-right">
          {{ sottotitolo }}
        </h5>

      </div>


    </div>

    <div>
    <ProvaSvg class="mx-auto d-block" />
    </div>
  </div>


</template>

<script>

import ProvaSvg from "~/assets/svg/frecciahover.svg?inline";
import GifInizio from "~/assets/svg/frecciahover.svg?inline";
import ScrollArrow from "~/assets/svg/provauno.svg?inline";

export default {
  name: 'FirstSection',
  components: {ScrollArrow, ProvaSvg},
  props: ['sottotitolo', 'imgSrc'],
}

</script>

<style>

.sectionone {
  height: 100vh;
  background-color: white;
}

.gifcover {
  width: 90%;
}

.rightsubtitle{
  text-align: right;
  max-width: 720px;
}

@media (max-width: 768px) {

  .sectionone {
    height: auto;

  }

}

</style>
