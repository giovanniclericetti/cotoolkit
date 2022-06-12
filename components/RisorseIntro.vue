<template>

<div class="introrisorse m-5 pt-5 nomargin">

  <div class="row my-5 pt-5 nomargin">

    <div class="col-md-3">

      <div>

        <div class="iconrisorse">
          <!--<img :srsc="imgSrcIcon">-->
          <img src="~assets/svg/co-framework.svg">
        </div>

        <div class="mt-4">

        <div>
          <b-button class="pills py-0 m-1" block> 8 STEP </b-button>
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

      <b-container>
        <b-row class="risorsetab py-3 mt-5">

          <b-col md="auto" style="border-right: solid 2px #E4E3E3" class="px-5">

            <div style="font-size: 20px" >
              <b> Durata attività </b>
            </div>
            <div class="tab_info">
              {{ durata }}
            </div>

          </b-col>

          <b-col md="auto" style="border-right: solid 2px #E4E3E3;" class="px-5">



            <div style="font-size: 20px" >
              <b> Numero partecipanti </b>
            </div>
            <div class="tab_info">
              {{ partecipanti }}
            </div>



          </b-col>

          <b-col md="auto" class="px-5" >

            <div style="font-size: 20px">
              <b> Tipologia </b>
            </div>
            <div class="tab_info">
              {{ tipologia }}
            </div>

          </b-col>

        </b-row>

      </b-container>



    </div>

  </div>



</div>


</template>

<script>
export default {
  name: "Risorse_Intro",
  props: ['imgSrcIcon', 'PillsColor','title', 'durata', 'partecipanti', 'tipologia']
}
</script>

<style>



.risorsetab{
  background-color: #F9F9F9;
  width: 90%;
  border-radius: 20px;
  text-align: left;
  box-shadow: 0px 0px 12px rgba(0, 0, 0, 0.12);
}

.pills{
  border-radius: 5px;
  background-color: #FCBB16;
  border: none;
}

.pills:hover{
  background-color: #FCBB16;
  cursor: default;
}


.tab_info{
  font-size: 18px;
  font-weight: bold;
  color: #FCBB16;
}

.iconrisorse{
  width: 80%;
}

@media (max-width: 768px) {

  .iconrisorse{
    display: none;
  }

  .introrisorse{

  }


}

</style>
