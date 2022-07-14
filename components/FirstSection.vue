<template>

  <div class="container-fluid sectionone mt-5 py-5">
    <div class="row align-items-center p-md-5">
      <div class="col-md-7">

        <h2 class="mb-4 testifirstsection" >
          {{ title }}
        </h2>

        <h5>
          <slot/>
        </h5>

      </div>

      <div class="col mt-5">

        <img class="gifcover" src="~assets/images/homepage.gif">

      </div>
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
  props: ['title', 'imgSrc'],
}

</script>

<style>

.sectionone {
  height: 100vh;
  background-color: white;
}

.gifcover {
  width: 100%;
}

.testifirstsection{
  font-size: 65px
}

@media (max-width: 768px) {

  .sectionone {
    height: auto;

  }
  .testifirstsection{
    font-size: 50px
  }


}

</style>
