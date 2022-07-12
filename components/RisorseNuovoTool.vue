<template>


    <div class="m-1  m-md-0 row align-items-center p-md-5 ">
      <div class="col-md-7">

        <h2 class="mb-md-4">
          {{ title }}
        </h2>

        <p>
          <slot/>
        </p>

      </div>

      <div class="col-md-5 justify-content-md-center">

        <img class="gifcover" src="~assets/images/mail.gif">

      </div>



      <b-row class="container my-md-5 justify-content-center" style="text-align: center">
<b-col>
        <ButtonContact>
          Contattaci
        </ButtonContact>
</b-col>
      </b-row>





    </div>






</template>

<script>

import ProvaSvg from "~/assets/svg/frecciahover.svg?inline";
import GifInizio from "~/assets/svg/frecciahover.svg?inline";
import ScrollArrow from "~/assets/svg/provauno.svg?inline";

export default {
  name: 'FirstSection',
  components: {ScrollArrow, ProvaSvg},
  props: ['title', 'imgSrc'],
}

</script>

<style>

.gifcover {
  width: 100%;
}

@media (max-width: 768px) {

  .sectionone {
    height: auto;

  }

}

</style>
