<template>

  <div class="theme-blue">
    <Navbar/>

<b-link class="indietro h2" to="/risorse/">
  <b-icon icon="arrow-left-short" class="d-none d-lg-block"></b-icon>
  <b-icon icon="arrow-left-circle-fill" class="d-block d-lg-none"></b-icon>
</b-link>

    <div class="container justify-content-center">

      <RisorseIntro
      imgSrcIcon="~assets/svg/about_figmapack.svg"
      title="Stakeholder Analysis"
      durata="20/40 minuti"
      partecipanti="1 persona"
      tipologia="per il designer"
      pill1="STAKEHOLDER"
      pill2="CLUSTER"
      pill3="SCELTE"
      pill4="PESO DECISIONALE"
      iconrisorsa="r-stakeholder"

      >

        È uno strumento veloce ed affidabile che gestisce i cluster di utenti in base a due parametri: il potere e l’interesse. Il potere di uno stakeholder definisce quanto questo possa influenzare le varie decisioni prese riguardo il progetto. Il fattore “interesse” invece si basa sull’impatto che le decisioni progettuali prese avranno sull'esperienza dell’utente.
      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/stakeholder.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Questo tool ti supporta nell'identificare gli stakeholder che parteciperanno al tuo progetto. Lo scopo è aiutarti a prendere in considerazione tutti coloro che influiscono in modo significativo su una decisione, o che potrebbero esserne influenzati da questa. Identificare chi ha potere decisionale e su chi le scelte prese ricadranno in modo più significativo può aiutare ad allineare le decisioni sulla base dei diversi cluster interessati. L'analisi degli stakeholder può aiutarti a sviluppare una strategia efficace per prendere decisioni finali e intermedie sulla base delle esigenze di determinati cluster particolarmente significativi per quella fase, gestendone le aspettative.    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      1. Creare una lista di tutte le possibili parti interessate e scrivere ognuna di esse su un post-it.
      <br> <br> 2. Organizzare le parti interessate sul grafico bidimensionale (cartesiano) qualificandole con un quantità di potere e interesse tra "basso" o "alto".
      <br> <br> 3. La strategia progettuale dovrà tenere conto dei differenti cluster di stakeholder e le loro differenti esigenze e gradi di interesse per soddisfare tutti in modo trasversale.

    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              definire quali scelte progettuali implementare sulla base delle ricadute sui diversi cluster di stakeholders
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            prendere scelte co-progettate sulla base della posizione sul grafico della tipologia di cluster da cui arriva la proposta.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/modulidinvito/">
            <b-icon icon="arrow-left-circle-fill"></b-icon>
          </b-link>
        </b-col>

        <b-col class="col-10">

          <p style="color: white">
            Accedi al Figma pack <br>
            e inizia ad usare questo tool
          </p>

          <div>

            <ButtonFigma>
              Accedi al pack
            </ButtonFigma>

          </div>



        </b-col>

        <b-col class="col-1">
          <b-link class="whiteicon h2" to="/ritrattocinese/">
            <b-icon icon="arrow-right-circle-fill" ></b-icon>
          </b-link>
        </b-col>

      </b-row>

    </div>

    <Footer/>

  </div>



</template>

<script>

export default {
  name: 'Co-Framework'
}

</script>

<style>

.indietro{
  position: fixed;
  top: 80px;
  left: 20px;
  color: black;
}

.indietro:hover{
  color: black;
}


</style>

