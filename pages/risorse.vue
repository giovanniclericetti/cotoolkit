<template>
  <div class="theme-green">

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

    <div class="container align-left py-5">

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

          <b-col> <b-link to="/co-framework/">
            <div class="boxhover p-4 shadow">
              <coframework class="p-4"/>
              <BoxHover risorsa="Co-framework">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col>
            <div class="boxhover p-4 shadow">
              <handbook class="p-4"/>
              <BoxHover risorsa="Co-framework">
              </BoxHover>
            </div>
          </b-col>


          <b-col>
            <div class="boxhover p-4 shadow">
              <tavola class="p-4"/>
              <BoxHover risorsa="tavola">
              </BoxHover>
            </div>
          </b-col>




        </b-row>
      </b-container>





    </div>

    <div class="align-left py-2" style="background-color: #F9F9F9">

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
            <div class="boxhover p-4 shadow">
              <coframework class="p-4"/>
              <BoxHover risorsa="Co-framework">
              </BoxHover>
            </div>
          </b-col>

          <b-col>
            <div class="boxhover p-4 shadow">
              <handbook class="p-4"/>
              <BoxHover risorsa="Co-framework">
              </BoxHover>
            </div>
          </b-col>


          <b-col>
            <div class="boxhover p-4 shadow">
              <tavola class="p-4"/>
              <BoxHover risorsa="tavola">
              </BoxHover>
            </div>
          </b-col>

        </b-row>
      </b-container>

    </div>

    <div class="container">
      <RisorseNuovoTool
        title="Proponi un nuovo tool per il tuo progetto"
      >

        Hai un metodo tutto tuo per fare branding e usi strumenti nuovi e fenomenali? Consigliaci i tuoi tool preferiti. Potremmo implementarli nel nuovo aggiornamento.
        <br> <br>
        <span style="color: #9747FF"> <b> >Stay tuned </b> </span>
      </RisorseNuovoTool>

    </div>

    <FilledSection
      sottotitolo="Apri un nuovo progetto su Figma, segui gli 8 step del Co-Framework e crea un nuovo brand collaborando con la community."
    >

      Inizia ad usare i tool

    </FilledSection>


    <Footer/>
  </div>




</template>

<script>

export default {
  name: 'Risorse',
  components: {coframework, handbook, tavola},
  props: [],
}

import coframework from "~/assets/svg/provauno.svg?inline";
import tavola from "~/assets/svg/ultima-01.svg?inline";
import handbook from "~/assets/svg/book.svg?inline";

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

svg .show-on-hover {
  opacity: 0;
  transition: 0.3s ease-in-out;

}

</style>

