<template>

  <div class="container-fluid sectionone mt-5 px-5" align-v="bottom" >

    <div class="row align-items-center p-5">

      <div class="col-md-6 col-6">

        <img class="gifcover" :src="require(`~/assets/images/${gifabout}.gif`)" />

      </div>

      <div class="col-md-6">

        <h2 class="mb-4" style="max-width:700px">
          <slot/>
        </h2>

        <h5 class="text-right">
          {{ sottotitolo }}
        </h5>


    </div>

    <div>
    <ProvaSvg class="mx-auto d-block" />
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


@media (max-width: 768px) {

  .sectionone {
    height: auto;

  }

}

</style>
