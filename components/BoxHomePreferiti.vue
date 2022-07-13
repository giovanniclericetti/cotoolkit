<template>
  <b-card class="overflow-hidden cardhome tools h-md-50 boxhomebg" style="height:auto" align-v="center" >

    <b-row align-v="center" class="h-100" >
      <b-col class="desktop">
        <b-card-body>
          <b-card-text>
            <h3 style="font-size: 50px">
              Mandaci <br> i tuoi tool <br>
              <span style="color:#9747FF;
"> preferiti </span> </h3>
          </b-card-text>
        </b-card-body>
      </b-col>

      <b-col class="mobile" style="height: 170px">
        <b-card-body>
          <b-card-text >
            <h3 style="font-size: 35px; max-width: 200px">
              Mandaci <br> i tuoi tool <br>
              <span style="color:#9747FF;
"> preferiti </span> </h3>
            </h3>

          </b-card-text>
        </b-card-body>
      </b-col>


    </b-row>
  </b-card>
</template>

<script>
export default {
  name: "BoxHomePreferiti"
}
</script>

<style scoped>
.tools{
  background-image: url("~assets/svg/card5.svg");
  background-size: 120%;
  transition: 0.3s ease-in-out;}

.boxhomebg:hover{
  background-size: 130%;
  transition: 0.3s ease-in-out;
}

@media (max-width: 768px) {
  .tools{
    background-image: url("~assets/svg/card5mobile.svg");
  }
}



</style>
