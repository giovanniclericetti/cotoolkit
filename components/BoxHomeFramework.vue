<template>
   <b-card class="overflow-hidden cardhome">
      <b-row align-v="center" class="desktop">

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
          <b-card-img id="hoverimage" src="~assets/svg/card1.svg"></b-card-img>
        </b-col>

      </b-row>

     <b-row class="mobile sfondo">

     <b-col style="height: 170px;">
       <b-card-body>
         <b-card-text >
           <h3 style="font-size: 20px; max-width: 200px;">
             Scopri il nostro Framework
           </h3>
           <p style="font-size: 15px; max-width: 200px;">
             Uno strumento inturitivo per co-creare in modo veloce e collaborativo seguendo 8 semplici step.
           </p>

         </b-card-text>
       </b-card-body>
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
  cursor: pointer;
}

@media (max-width: 768px) {

  .sfondo{
    background-image: url("~assets/svg/card1mobile.svg");
    background-size: cover;

  }

}



</style>
