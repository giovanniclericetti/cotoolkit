<template>


  <b-card class="overflow-hidden cardhome boxhomebg tools h-100" align-v="center" >

    <b-row class="h-100" >
      <b-col class="desktop">
        <b-card-body>
          <b-card-text align-v="start" style="margin-top: 40%">
            <h3 style="font-size: 50px;">
              Scopri di più sul progetto
            </h3>

          </b-card-text>
        </b-card-body>
      </b-col>

      <b-col class="mobile" style="height: 170px" >
        <b-card-body>
          <b-card-text >
            <h3 style="font-size: 35px; max-width: 200px">
              Scopri di più sul progetto
            </h3>

          </b-card-text>
        </b-card-body>
      </b-col>


    </b-row>
  </b-card>







</template>

<script>
export default {
  name: "BoxHomeProject"
}
</script>

<style scoped>

.tools{
  background-image: url("~assets/svg/card4.svg");
  background-size: 120%;
  transition: 0.3s ease-in-out;
}

.boxhomebg:hover{
  background-size: 130%;
  transition: 0.3s ease-in-out;
}

@media (max-width: 768px) {
  .tools{
    background-image: url("~assets/svg/card4mobile.svg");
  }
}

</style>
