<template>
  <b-card class="overflow-hidden cardhome tools boxhomebg" style="height:auto" align-v="center" >

    <b-row align-v="center" class="h-100" >
      <b-col class="desktop">
        <b-card-body>
          <b-card-text style="color: white">
            <h3 style="font-size: 50px">
              Powered by
            </h3>
            <h3 style="font-size: 100px">
              Figma
            </h3>
          </b-card-text>
        </b-card-body>
      </b-col>

      <b-col class="mobile" style="height: 170px">
        <b-card-body class="my-2">
          <b-card-text >
            <h3 style="font-size: 35px; max-width: 200px; color: white">
              Powered by
            </h3>
            <h3 style="font-size: 60px; max-width: 200px; color: white">
              Figma
            </h3>

          </b-card-text>
        </b-card-body>
      </b-col>

    </b-row>
  </b-card>
</template>

<script>
export default {
  name: "BoxHomeFigma"
}
</script>

<style scoped>
.tools{
  background-image: url("~assets/svg/card6.png");
  background-size: 100%;
  transition: 0.3s ease-in-out;
}

.boxhomebg:hover{
  background-size: 150%;
  transition: 0.3s ease-in-out;
}

</style>
