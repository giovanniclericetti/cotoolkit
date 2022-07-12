<template>

  <div class="container-fluid
   sectionone mt-md-3 mt-5 mx-2" align-v="bottom" >

    <div class="row align-items-center p-md-5">

      <div class="col-md-6 col-12  gifintro">

        <img class="gifcover" :src="require(`~/assets/images/${gifabout}.gif`)" />

      </div>

      <div class="col-md-6 testisection testintro">

        <h2 class="mb-4" style="max-width:700px">
          <slot/>
        </h2>

        <h5 class="text-right">
          {{ sottotitolo }}
        </h5>


    </div>
      <div  style="order: 4; text-align: center" >
        <b-link class="h2" to="#inizioabout">
          <b-icon icon="arrow-down-circle-fill" class="iconhover"></b-icon>
        </b-link>
      </div>
  </div>



  </div>


</template>

<script>

import ProvaSvg from "~/assets/svg/freccia.svg?inline";

import ScrollArrow from "~/assets/svg/provauno.svg?inline";

export default {
  name: 'FirstSection',
  components: {ScrollArrow, ProvaSvg},
  props: ['title', 'imgSrc', 'gifabout', 'sottotitolo'],
}

</script>

<style>

.sectionone {
  height: 98vh;
  background-color: white;
}

.gifcover {
  width: 100%;
}

.testintro{
  order: 2;
}

.gifintro{
  order: 1;
}


@media (max-width: 768px) {

  .sectionone {
    height: auto;

  }

  .testintro{
    order: 1;
  }

  .gifintro{
    order: 2;
  }

  .testisection {
    order: 1;
    text-align: left;
    font-size: 20px;
    max-width: 390px;
  }

}

</style>
