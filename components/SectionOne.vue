<template>

  <div class="container-fluid sectionone mt-5 p-5">
    <div class="row align-items-center p-5">

      <div class="col-md-6">

        <img :src="imgSrc">

      </div>

      <div class="col-md-5">

        <p>
          <slot/>
        </p>

      </div>


    </div>

    <div>
    <ProvaSvg class="mx-auto d-block" />
    </div>
  </div>


</template>

<script>

import ProvaSvg from "~/assets/svg/freccia.svg?inline";

import ScrollArrow from "~/assets/svg/provauno.svg?inline";

export default {
  name: 'FirstSection',
  components: {ScrollArrow, ProvaSvg},
  props: ['title', 'imgSrc'],
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
