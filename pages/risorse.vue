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
      per <i> co-creare </i> in modo
      semplice e guidato

    </FirstSectionDx>



    <div class="container align-left py-5" id="perprogettare">

      <RisorseSection
        title="Per Progettare"
      >

        <div style="max-width: 680px" class="theme-yellow">

          <span style="color: var(--color-primary); font-weight: 500" > Usa questi tool </span> per impostare il progetto,
          avere delle linee guida da seguire e conoscere
          di più come si affronta un lavoro di Co-design per il branding.

        </div>

      </RisorseSection>
    <div class="container">
      <b-container class="mb-md-5 container" >
        <b-row cols="2" cols-sm="2" cols-md="2" cols-lg="4" class="g-3">

          <b-col class=" p-1"> <b-link to="/co-framework/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 ">
              <coframeworkicon class="p-2 iconcine"

              />
              <BoxHover risorsa="Co-Framework">
              </BoxHover>
            </div>
          </b-link>
          </b-col>

          <b-col class=" p-1"> <b-link to="/handbook/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 ">
              <handbook class="p-2 iconcine"/>
              <BoxHover risorsa="Co-design Handbook">
              </BoxHover>
            </div> </b-link>
          </b-col>


          <b-col class=" p-1"> <b-link to="/tavola/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5">
              <tavola class="p-2 iconcine" />
              <BoxHover risorsa="Tavola di Progetto">
              </BoxHover>
            </div> </b-link>
          </b-col>

        </b-row>
      </b-container>




    </div>

    </div>

    <div class="container align-left py-2 pb-md-5" id="stakeholders" style="max-width: 100vw; background-color: #F9F9F9;">

      <RisorseSection
        title="Per il rapporto con gli Stakeholders"
      >

        <div style="max-width: 1020px" class="theme-blue">

          <span style="color: var(--color-primary); font-weight: 500" > Usa questi tool </span> per analizzare i cluster di stakeholder che prenderanno parte al progetto, invitarli a partecipare alle varie attività di co-creazione e definire all’origine qual è la situazione del brand prima che il progetto cominci.

        </div>

      </RisorseSection>
      <div class="container">
      <b-container class="mb-md-5">
        <b-row cols="2" cols-sm="2" cols-md="2" cols-lg="4" class="g-3">

          <b-col> <b-link to="/questionario/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 5">
              <questionario class="p-2 iconcine"/>
              <BoxHover risorsa="Questionario">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/modulidinvito/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 ">
              <moduli class="p-2 iconcine" />
              <BoxHover risorsa="Moduli d'invito">
              </BoxHover>
            </div> </b-link>
          </b-col>


          <b-col> <b-link to="/stakeholderanalysis/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 mb-5">
              <stakeholder class="p-2 iconcine" />
              <BoxHover risorsa="Stakeholder Analysis">
              </BoxHover>
            </div> </b-link>
          </b-col>

        </b-row>
      </b-container>
      </div>
    </div>

    <div class="container align-left py-5" id="asincrono">

      <RisorseSection
        title="Per il Workshop Asincrono"
      >

        <div style="max-width: 680px" class="theme-green">

          <span style="color: var(--color-primary); font-weight: 500" > Usa questi tool </span> per raccogliere informazioni, ottenere suggestioni e comprendere il sentiment del brand dal punto di vista degli stakeholder.

        </div>

      </RisorseSection>
    <div class="container">
      <b-container class="mb-md-5">
        <b-row cols="2" cols-sm="2" cols-md="2" cols-lg="4" class="g-3">

          <b-col> <b-link to="/ritrattocinese/" class="linkhover">
            <div class="boxhover py-3 shadow mb-md-5 ">
              <ritratto class="p-2 iconcine" />
              <BoxHover risorsa="Ritratto Cinese">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/tagcloud/" class="linkhover">
            <div class="boxhover py-3 shadow mb-md-5">
              <tag class="p-2 iconcine" />
              <BoxHover risorsa="Tag Cloud">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/mindmap/" class="linkhover">
            <div class="boxhover py-3 shadow mb-md-5 ">
              <mindmap class="p-2 iconcine" />
              <BoxHover risorsa="Mindmap">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/moodboard/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5">
              <mood class="p-2 iconcine" />
              <BoxHover risorsa="Moodboard">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/onlynessstatement/" class="linkhover">
            <div class="boxhover p-3 shadow mt-md-4 mb-md-5 mb-5">
              <only class="p-2 iconcine" />
              <BoxHover risorsa="Onlyness Statement">
              </BoxHover>
            </div> </b-link>
          </b-col>


        </b-row>
      </b-container>

    </div>
  </div>


    <div class="container align-left py-5 " style="background-color: #F9F9F9; max-width: 100vw;" id="sincrono">

      <RisorseSection
        title="Per il Workshop Sincrono"
      >

        <div style="max-width: 1010px" class="theme-green">

          <span style="color: var(--color-primary); font-weight: 500" > Usa questi tool </span> per condurre un workshop di Co-design volto a definire gli elementi alla base del nuovo brand. Sia intangibili come valori, tono di voce, punti di forza e debolezza; sia tangibili come palette, logo e touchpoint.

        </div>

      </RisorseSection>

      <div class="container">
      <b-container class="mb-md-5">
        <b-row cols="2" cols-sm="2" cols-md="2" cols-lg="4" class="g-3">

          <b-col> <b-link to="/definizionevalori/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 ">
              <valori class="p-2 iconcine" />
              <BoxHover risorsa="Definizione Valori">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/roleplaying/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 ">
              <role class="p-2 iconcine" />
              <BoxHover risorsa="Role Playing">
              </BoxHover>
            </div> </b-link>
          </b-col>


          <b-col> <b-link to="/howmightwe/" class="linkhover">
            <div class="boxhover p-3 shadow mb-md-5 s">
              <how class="p-2 iconcine" />
              <BoxHover risorsa="How Might We">
              </BoxHover>
            </div> </b-link>
          </b-col>

          <b-col> <b-link to="/crazy8/" class="linkhover">
            <div class="boxhover p-3 shadow mb-5">
              <crazy class="p-2 iconcine" />
              <BoxHover risorsa="Crazy 8">
              </BoxHover>
            </div> </b-link>
          </b-col>

        </b-row>
      </b-container>

    </div>
    </div>










    <div class="container">
      <RisorseNuovoTool
        title="Proponi un nuovo tool per il tuo progetto"
        class="my-5 mb-md-2"
      >

        Hai un metodo tutto tuo per fare branding e usi strumenti nuovi e fenomenali? Consigliaci i tuoi tool preferiti. Potremmo implementarli nel nuovo aggiornamento.

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
  components: {coframeworkicon, handbook, valori, role, how, crazy, tavola, questionario, moduli, stakeholder, tag, ritratto, mindmap, mood, only},
  props: [],
}

import coframeworkicon from "~/assets/svg/r-coframework.svg?inline";
import handbook from "~/assets/svg/r-book.svg?inline";
import tavola from "~/assets/svg/r-tavoladiprogetto.svg?inline";
import questionario from "~/assets/svg/r-questionario.svg?inline";
import moduli from "~/assets/svg/r-moduli.svg?inline";
import stakeholder from "~/assets/svg/r-stakeholder.svg?inline";
import ritratto from "~/assets/svg/r-ritratto.svg?inline";
import tag from "~/assets/svg/r-cloud.svg?inline";
import mindmap from "~/assets/svg/r-mindmap.svg?inline";
import mood from "~/assets/svg/r-moodboard.svg?inline";
import only from "~/assets/svg/r-onlyness.svg?inline";
import valori from "~/assets/svg/r-valori.svg?inline";
import role from "~/assets/svg/r-role.svg?inline";
import how from "~/assets/svg/r-howmight.svg?inline";
import crazy from "~/assets/svg/r-crazy.svg?inline";


</script>

<style>

.boxhover{
  max-width: 250px;
  max-height: 250px;
  background-color: #F9F9F9;
  border-radius: 30px;
  font-size: 18px;
  text-align: center;
}

.linkhover:hover{
  color: black;
}

.iconcine{
  max-height: 160px
}

@media (max-width: 768px) {

  .boxhover{
    width: 155px;
    height: 155px;
  }

  .iconcine{
    max-height: 100px
  }

  }


</style>

