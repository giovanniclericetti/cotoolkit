<template>

  <div class="container-fluid sectionone mt-5 px-5 shadow">

    <div class="row align-items-center px-5 " align-v="center">
      <div class="col">

        <img class="gifcover" :src="require(`~/assets/images/${gifdx}.gif`)" />

      </div>

      <div class="col-md-6 rightsubtitle">

        <h2 class="mb-4">
          <slot/>
        </h2>

        <h5 class="text-right">
          {{ sottotitolo }}
        </h5>

      </div>

      <div >
        <b-dropdown id="dropdown-1"
                    class="m-md-2 drophome shadow p-1 mx-md-5"
                    style="border-radius: 10px; font-size: 22px; font-weight: 700;"
                    split-variant="outline-primary"
                    variant="white"
                    size="lg"
                    text="Elenco Tool"

                 >
          <b-dropdown-item class="dropmenu"  to="#perprogettare"> Per Progettare </b-dropdown-item>
          <b-dropdown-item class="dropmenu" to="#stakeholders"> Rapporto con gli Stakeholders </b-dropdown-item>
          <b-dropdown-item class="dropmenu" to="#asincrono"> Workshop Asincrono </b-dropdown-item>
          <b-dropdown-item class="dropmenu" to="#sincrono"> Workshop Sincrono </b-dropdown-item>
        </b-dropdown>
      </div>

    </div>


    <!--
    <div>
    <ProvaSvg1 class="mx-auto d-block" />
    </div>
-->

  </div>


</template>

<script>

import ProvaSvg1 from "~/assets/svg/frecciahover.svg?inline";
import GifInizio from "~/assets/svg/frecciahover.svg?inline";
import ScrollArrow from "~/assets/svg/provauno.svg?inline";

export default {
  name: 'FirstSection',
  components: {ScrollArrow, ProvaSvg1},
  props: ['sottotitolo', 'imgSrc', 'gifdx'],
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

.dropmenu{
  font-size: 20px;
  background-color: white;
}

.drophome{
  font-size: 22px;
  background-color: white;
}

.dropmenu:hover{
  background-color: #F9F9F9;
}


@media (max-width: 768px) {

  .sectionone {
    height: auto;

  }

}

</style>
