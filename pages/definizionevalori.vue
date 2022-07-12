<template>

  <div class="theme-green">
    <Navbar/>

<b-link class="indietro h2" to="/risorse/">
  <b-icon icon="arrow-left-short" class="d-none d-lg-block"></b-icon>
  <b-icon icon="arrow-left-circle-fill" class="d-block d-lg-none"></b-icon>
</b-link>

    <div class="container justify-content-center">

      <RisorseIntro
      imgSrcIcon="~assets/svg/about_figmapack.svg"
      title="Definizione Valori"
      durata="10/15 minuti"
      partecipanti="2/20 persone"
      tipologia="Sincrono"
      pill1="SELEZIONE"
      pill2="UNICITÀ"
      pill3="BRAND VALUES"
      pill4="VALORI"
      iconrisorsa="r-valori"

      >

        Alla base dell’identità di una marca ben strutturata devono esserci pochi (4-5) valori, univoci e ben definiti che devono sottendere a tutte le scelte progettuali e di esperessione della marca stessa in ogni sua forma.       </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/valori.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      La definizione dei valori è un esercizio fondamentale per esplorare quali sono i valori portanti del brand e attorno a cosa devono essere prese le scelte di marca in tema di identità, ma non solo.   </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Viene fatto in modo intuitivo e rapido, per incoraggiare i partecipanti a seguire la loro sensazione, piuttosto che pensarci troppo e cercare di trovare i valori "corretti". È un buon esercizio da utilizzare per avviare la riflessione e il dialogo sui valori personali. Attraverso un processo a “imbuto” si andranno man mano a scartare i valori ritenuti superflui andando e definire quali sono i veri pilastri che reggeranno la marca.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              Definire 4-5 valori che fungano da linee guida per tutte le scelte che riguarderanno questo progetto di branding o rebranding.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            Procedere ad “imbuto” dando poco tempo agli stakeholder per ragionare, favorendo così un pensiero emozionale/immediato.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/onlynessstatement/">
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
          <b-link class="whiteicon h2" to="/roleplaying/">
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

