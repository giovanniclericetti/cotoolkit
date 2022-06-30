<template>
   <b-card class="overflow-hidden cardhome">
      <b-row align-v="center">

        <b-col md="6">
          <b-card-body>
            <b-card-text >
              <h3 style="font-size: 50px">
                Scopri il nostro <br>
                Framework
              </h3>
              Uno strumento inturitivo per co-creare in modo veloce e collaborativo seguendo 8 semplici step.
            </b-card-text>
          </b-card-body>
        </b-col>

        <b-col md="6">
          <b-card-img src="~assets/svg/card1.svg"></b-card-img>
        </b-col>

      </b-row>
    </b-card>


</template>

<script>
export default {
  name: "BoxHomeFramework"
}
</script>

<style scoped>

.cardhome{
  border: none;
  border-radius: 20px;
  background-color: #F9F9F9;
  height: 100%;
}


</style>
