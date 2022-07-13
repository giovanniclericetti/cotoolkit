<template>
   <b-card class="overflow-hidden cardhome sfondo tools">
      <b-row align-v="center" class="h-100" >

        <b-col  class="desktop" >
          <b-card-body>
            <b-card-text  align-v="start" style="max-width: 450px;" >
              <h3 style="font-size: 50px; ">
                Scopri il nostro
                Framework
              </h3>
              Uno strumento inturitivo per co-creare in modo veloce e collaborativo seguendo 8 semplici step.

            </b-card-text>
          </b-card-body>
        </b-col>

     <b-col style="height: 170px;" class="mobile">
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

.sfondo{
  background-image: url("~assets/svg/card1.svg");
  background-size: 100%;
  transition: 0.3s ease-in-out;}

.sfondo:hover{
  background-size: 110%;
  transition: 0.3s ease-in-out;
}


@media (max-width: 768px) {

  .sfondo{
    background-image: url("~assets/svg/card1mobile.svg");
    background-size: cover;

  }


}



</style>
