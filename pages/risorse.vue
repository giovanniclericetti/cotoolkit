<template>
  <div class="">

    <div>
      <Navbar/>
    </div>

      <FirstSectionDx
        gifdx="risorse"
        sottotitolo="15 digital-tool completamente open source per aiutarti nel co-progettare l’intero processo di creazione di un nuovo brand"
      >

        Scopri gli strumenti <br>
        per <i> co-creare </i> in modo <br>
        semplice e guidato

        </FirstSectionDx>


    <div class="container align-left">

    <RisorseSection
    title="Per Progettare"
    >

      <div style="max-width: 680px">

    <span style="color: #FCBB16; font-weight: 500"> Usa questi tool </span> per impostare il progetto,
    avere delle linee guida da seguire e conoscere
    di più come si affronta un lavoro di Co-design per il branding.

    </div>

    </RisorseSection>

      <b-container class="bv-example-row mb-5">
        <b-row cols="2" cols-sm="2" cols-md="2" cols-lg="4">



          <b-col>

            <div class="boxhover p-4">

            <coframework class="p-4"/>

            <BoxHover risorsa="Co-framework">
            </BoxHover>

            </div>



          </b-col>

          <b-col>
            <div class="boxhover p-4">

              <coframework class="p-4"/>

              <BoxHover risorsa="Co-framework">
              </BoxHover>

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
  name: 'Risorse',
  components: {coframework},
  props: [],
}

import coframework from "~/assets/svg/provauno.svg?inline";

</script>

<style>

.boxhover{
  max-width: 240px;
  max-height: 240px;
  background-color: #F9F9F9;
  border-radius: 30px;
  font-size: 18px;
  text-align: center;
}


</style>

