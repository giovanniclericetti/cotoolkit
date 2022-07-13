<template>

  <b-card class="overflow-hidden cardhome tools boxhomebg" align-v="center" style="background-color: #24B265">

    <b-row class="h-100" >
      <b-col class="desktop">
        <b-card-body>
          <b-card-text style="color: white; margin-top: 40%" align-v="start">
            <h3 style="font-size: 50px;">
              Quali tool ti proponiamo?
            </h3>
            Abbiamo selezionato per te 14 tool collaborativi per il tuo progetto di branding. Scegli in autonomia quelli
            che ritieni più utili e inizia a co-creare insieme alla community.

          </b-card-text>
        </b-card-body>
      </b-col>

      <b-col class="mobile" style="height: 170px;">
        <b-card-body class="my-2">
          <b-card-text >
            <h3 style="font-size: 20px; max-width: 300px; color: white">
              Quali tool ti proponiamo?
            </h3>
            <p style="font-size: 15px; max-width: 300px; color: white">
              Abbiamo selezionato per te 14 tool collaborativi per il tuo progetto di branding. Scegli in autonomia quelli
              che ritieni più utili e inizia a co-creare insieme alla community.
            </p>

          </b-card-text>
        </b-card-body>
      </b-col>

    </b-row>

  </b-card>

</template>

<script>
export default {
  name: "BoxHomeTool"
}
</script>

<style scoped>

.tools{
  background-image: url("~assets/svg/card3.svg");
  background-size: 120%;
  transition: 0.3s ease-in-out;}

.boxhomebg:hover{
  background-size: 130%;
  transition: 0.3s ease-in-out;
}

@media (max-width: 768px) {

  .tools{
    background-image: url("~assets/svg/card3mobile.svg");
  }

}

</style>
