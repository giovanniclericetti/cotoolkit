<template>

  <div class="theme-yellow">
    <Navbar/>

<b-link class="indietro h2" to="/risorse/">
  <b-icon icon="arrow-left-short" class="d-none d-lg-block"></b-icon>
  <b-icon icon="arrow-left-circle-fill" class="d-block d-lg-none"></b-icon>
</b-link>

    <div class="container justify-content-center">

      <RisorseIntro
      imgSrcIcon="~assets/svg/about_figmapack.svg"
      title="Co-design Handbook"
      durata="10 minuti"
      partecipanti="1/100+ persone"
      tipologia="per il designer"
      pill1="DOWNLOAD"

      iconrisorsa="r-book"

      >
        Un breve manuale contenente informazioni e consigli sul Co-design e su come condurre un progetto usando questo modello. Un handbook digitale pratico ed estremamente utile se si sa poco della co-progettazione.
      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/handbook.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Una serie di slide contenenti consigli pratici e informazioni teoriche sul metodo progettuale di design thinking denominato Co-design. Un modello che fonda il suo essere nella collaborazione creativa tra designer e non designer, tra persone con competenze, necessità e sensibilità differenti, ma accomunati da un qualche legame con l’oggetto del progetto, in questo caso la marca. Il co-design prevede una collaborazione creativa volta al problem solving che scaturisce da questa diversità di punti di vista.

    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">
      Scarica il file .pdf dal bottone qui sopra. Usa le informazioni contenute al suo interno per prendere decisioni, impostare attività e relazionarti con gli stakeholder nel modo più funzionale e democratico possibile al fine di ottenere un progetto unilaterlamente co-progettato con il supporto della community.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              informarti sul Co-design e sulle sue pratiche, imparando a progettare seguendo i criteri dei questo modello.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            implementare nella pratica gli aspetti teorici contenuti all’interno dell’handbook, avendo sempre un approccio democratico.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/co-framework/">
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
          <b-link class="whiteicon h2" to="/tavoladiprogetto/">
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

