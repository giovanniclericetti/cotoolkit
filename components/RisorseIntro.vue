<template>

<div class="introrisorse m-5 pt-5">

  <div class="row">

    <div class="col-md-3">

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


    </div>

    <div class="col-md-9">

      <div class="container">
        <h3 class="mb-4">
          {{ title }}
        </h3>

        <p style="font-size: 22px">
          <slot/>
        </p>

      </div>

      <RisorseTab/>

    </div>

  </div>


  Ciao Belli

</div>


</template>

<script>
export default {
  name: "Risorse_Intro",
  props: ['imgSrcIcon', 'PillsColor','title']
}
</script>

<style>

.introrisorse{
  background-color: red;

}

.iconrisorsa{
  width: 70%;
}

.pills{
  border-radius: 5px;
  background-color: #FCBB16;
  border: none;
}

</style>
