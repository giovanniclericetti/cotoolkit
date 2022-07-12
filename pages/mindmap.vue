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
      title="Mind Map"
      durata="10/30 minuti"
      partecipanti="1/100+ persone"
      tipologia="Asincrono"
      pill1="VALORI"
      pill2="IMMAGINARIO DI MARCA"
      pill3="TOUCHPOINTS"
      pill4="BRAINSTORMING"
      iconrisorsa="r-mindmap"

      >

        Serve a mappare tutti i pensieri attorno a un argomento specifico, aiutandoci a costruire un modello mentale di esso. Sulla base di topic specifici si diramano argomenti ed elementi inerenti alla marca.      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/mindmap.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Una mappa mentale o “mind map” è una forma di rappresentazione grafica del pensiero teorizzata dall’autore inglese Tony Buzan. Serve a organizzare e analizzare idee e concetti, andare in profondità
      e favorire un apprendimento visuale più intuitivo e immediato, fare brainstorming e problem solving allenando la creatività. Rispetto al mondo del branding, risulta molto utile ad organizzare tutti gli aspetti fisici e mentali collegati alla marca.   </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Inizia mettendo il nome del brand al centro di una superficie vuota, quindi annota altre parole, segni, disegni, tematiche attorno ad esso. Lascia liberi gli stakeholder di scrivere qualunque parola o concetto, mostrando sempre la connessione con il punto iniziale, o i collegamenti tra loro. Lascia che la loro mente sia libera di esplorare, divergere e connettere punti, rendendo la mappa sempre più grande: ci sarà tempo in seguito per rivederla e razionalizzarla.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              incoraggiare il pensiero libero e scoprire connessioni interessanti tra diversi aspetti collegati alla marca.            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            favorire singole parole, immagini o frasi brevi in modo tale da mappare singoli concetti base e creare in seguito connessioni complesse.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/tagcloud/">
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
          <b-link class="whiteicon h2" to="/moodboard/">
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

