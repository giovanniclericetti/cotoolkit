<template>

  <div class="theme-red">
    <Navbar/>

<b-link class="indietro h2" to="/risorse/">
  <b-icon icon="arrow-left-short" class="d-none d-lg-block"></b-icon>
  <b-icon icon="arrow-left-circle-fill" class="d-block d-lg-none"></b-icon>
</b-link>

    <div class="container justify-content-center">

      <RisorseIntro
      imgSrcIcon="~assets/svg/about_figmapack.svg"
      title="Tavola di Progetto"
      durata="l'intero progetto"
      partecipanti="1 persona"
      tipologia="per il designer"
      pill1="BRANDING"
      pill2="MARCA"
      pill3="PUNTI CARDINE"
      pill4="RECAP"
      iconrisorsa="r-tavoladiprogetto"

      >

        Una visualizzazione riassuntiva di tutti gli elementi cardine del progetto. Qui sono contenuti sia elementi testuali, come valori, pt. di forza, debolezze, etc., sia visivi, come moodboard, varie versioni del logo, power application, etc.

      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/tavoladiprogetto.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Questo tool ha lo scopo di riassumere l’intero progetto di branding/rebranding, tanto per il desiger quanto per i co-designer. Non ha lo stesso scopo di una presentazione finale al cliente, ma serve più come collettore di informazioni definite e consolidate, schematizzate in un unico spazio delimitato.
    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      È da utilizzarsi verso la fine del percorso come schema riassuntivo, sia per te, designer, per riordinare i concetti e le idee che sottendono tutto il progetto, sia per gli stakeholder, per comprendere a pieno l’interezza del lavoro di branding. Non c’è una pratica giusta di utilizzo: in generale, vanno inseriti all’interno delle varie TAB i diversi elementi testuali e visivi già definiti in precedenza.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              raccogliere e schematizzare visivamente tutti i capi saldi e gli elementi fondanti del tuo progetto di branding/rebranding.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            Non modificare in extremis elementi già definiti. Inserisci solo concetti o immagini già consolidate ed approvate dal cliente.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/handbook/">
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
          <b-link class="whiteicon h2" to="/questionario/">
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

