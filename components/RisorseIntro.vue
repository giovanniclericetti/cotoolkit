<template>

  <div class="introrisorse pt-5 container">

    <b-row class=" my-5 pt-5 mx-md-5" >

      <b-col class="col-md-4 col-12">

          <div class="iconrisorse my-3">
            <img :src="require(`~/assets/svg/${iconrisorsa}.svg`)">
          </div>

      </b-col>

      <b-col class="col-md-8" >

        <div>
          <h3 class="mb-4">
            {{ title }}
          </h3>

          <p class="mb-0 mb-md-4">
            <slot/>
          </p>

        </div>

      </b-col>

      <b-col class="col-md-4 col-12 py-3 container my-3 my-md-0">

        <div>
          <b-button block class="pills py-0 m-1"> {{pill1}} </b-button>
          <b-button class="pills py-0 m-1"> {{pill2}} </b-button>
        </div>
        <div>
          <b-button class="pills py-0 m-1"> {{pill3}} </b-button>
          <b-button class="pills py-0 m-1"> {{pill4}} </b-button>
        </div>

      </b-col>

      <b-col class="">

          <b-row class="risorsetab py-3  m-0 ">

            <b-col class="px-3 px-md-5 withborderdx py-md-0 py-2 col-6 boxcolorati" md="auto">
              <div >
                <b> Durata attività </b>
              </div>
              <div class="tab_info">
                {{ durata }}
              </div>
            </b-col>

            <b-col class="px-md-3 px-4 px-md-5 py-md-0 py-2 boxcolorati col-6 " md="auto" order-md="2">
              <div >
                <b> Tipologia </b>
              </div>
              <div class="tab_info">
                {{ tipologia }}
              </div>
            </b-col>

            <b-col class="px-3 px-md-5 withborderdx py-md-0 py-2 mt-3 mt-md-0 boxcolorati col-7" md="auto">
              <div  >
                <b> Numero partecipanti </b>
              </div>
              <div class="tab_info">
                {{ partecipanti }}
              </div>
            </b-col>

            <b-col class="px-md-5 py-md-0 py-2 px-4 mt-3 boxcolorati col-3 d-block d-lg-none" md="auto" >
              <img class="iconresponsive" :src="require(`~/assets/svg/${iconrisorsa}.svg`)">
            </b-col>



          </b-row>

        </b-container>



      </b-col>

    </b-row>



  </div>


</template>

<script>
export default {
  name: "Risorse_Intro",
  props: ['imgSrcIcon', 'iconrisorsa', 'PillsColor','title', 'durata', 'partecipanti', 'tipologia', 'pill1', 'pill2', 'pill3', 'pill4']
}
</script>

<style>



.risorsetab{
  background-color: #F9F9F9;
  border-radius: 20px;
  text-align: left;
  box-shadow: 0px 0px 12px rgba(0, 0, 0, 0.12);
}

.pills{
  border-radius: 5px;
  background-color: var(--color-primary);
  border: none;
}

.pills:hover{
  background-color: var(--color-primary);
  cursor: default;
}


.tab_info{
  font-size: 18px;
  font-weight: bold;
  color: var(--color-primary);
}

.iconrisorse{
  height: 50%;
}

.iconrisorse img{
  max-height: 200px;
}

.withborderdx{
  border-right: solid 2px #E4E3E3
}

.boxcolorati{
  font-size: 20px
}

.iconresponsive{
  height: 100%;
}

@media (max-width: 768px) {

  .iconrisorse{
    display: none;
  }
  .boxcolorati{
    font-size: 18px
  }

  p{
    font-size: 20px;
  }
  .withborderdx{

  }
}

</style>
