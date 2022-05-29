<template>

<div class="introrisorse m-5 pt-5">

  <div class="row align-items-center">

    <div class="col-md-4 bg-primary">

      <div>

        <div class="iconrisorsa">
          <!--<img :src="imgSrcIcon">-->
          <img src="~assets/svg/co-framework.svg">
        </div>

        <div class="mt-4">

        <div>
          <b-button class="pills py-0 m-1"> 8 STEP </b-button>
          <b-button class="pills py-0 m-1"> TRIPLE DIAMOND </b-button>

        </div>
        <div>

          <b-button class="pills py-0 m-1"> PROGETTO </b-button>
          <b-button class="pills py-0 m-1"> GUIDA </b-button>

        </div>
        </div>

      </div>
  blu

    </div>

    <div class="col-md-8 bg-secondary">

      orange

    </div>

  </div>


  Ciao Belli

</div>


</template>

<script>
export default {
  name: "Risorse_Intro",
  props: ['imgSrcIcon']
}
</script>

<style>

.introrisorse{
  background-color: red;
  height: 500px;
}

.iconrisorsa{
  width: 50%;
}

.pills{
  border-radius: 5px;
  background-color: "";
}

</style>
