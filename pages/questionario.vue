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
      title="Questionario"
      durata="10 minuti"
      partecipanti="1/100+ persone"
      tipologia="Google Form"
      pill1="BRAND SENTIMENT"
      pill2="DOMANDE"
      pill3="CONTATTI"
      pill4="STAKEHOLDER"
      iconrisorsa="r-questionario"

      >

        È uno strumento utile a raccogliere informazioni e pareri direttamente dagli stakeholder, in modo veloce e digitale. Inoltre può essere un ottimo “primo contatto” tra utenti e designer per iniziare a co-progettare.

      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/questionario.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Un questionario in generale, in particolare un Google Forms ti consente di raccogliere informazioni dagli utenti tramite quiz o sondaggi personalizzati. In questo caso le domande verteranno sul Brand Sentiment, il percepito di marca e l’esperienza diretta da parte degli stakeholder.    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Inizia creando o copiando un modulo. Scegli tra più tipi di domande, trascina e rilascia per riordinare le domande e personalizzare i valori con la stessa facilità con cui si incolla un elenco. Inivia il sondaggio e raccogli le risposte degli stakeholder. Puoi quindi collegare le informazioni a un foglio di lavoro per registrare automaticamente le risposte. Il foglio di calcolo, quindi, si popolerà con le risposte del quiz o del sondaggio in tempo reale. Usa queste risposte per definire alcuni punti di partenza o di criticità del progetto.    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              raccogliere informazioni preliminari sul Brand Sentiment ed il percepito di marca da parte degli stakeholder
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            strutturare un questionario che possa essere completato in massimo 10 minuti. Non esagerare con le domande!          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/tavoladiprogetto/">
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
          <b-link class="whiteicon h2" to="/modulidinvito/">
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

