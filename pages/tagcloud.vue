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
      title="Tag Cloud"
      durata="3/5 minuti"
      partecipanti="1/100+ persone"
      tipologia="Asincrono"
      pill1="PAROLE CHIAVE"
      pill2="CONCETTI"
      pill3="DATAVIZ"
      pill4="IMMAGINARIO DI MARCA"
      iconrisorsa="r-cloud"

      >

        È uno strumento veloce ed affidabile che gestisce i cluster di utenti in base a due parametri: il potere e l’interesse. Il potere di uno stakeholder definisce quanto questo possa influenzare le varie decisioni prese riguardo il progetto. Il fattore “interesse” invece si basa sull’impatto che le decisioni progettuali prese avranno sull'esperienza dell’utente.
      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/cloud.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Una Tag Cloud o Word Cloud, letteralmente “nuvola di parole”, è un'immagine composta interamente da parole. Le parole variano per dimensioni e/o colore. Le parole più grandi, o più sature, suggeriscono una frequenza o un utilizzo più elevati. La maggiore frequenza indica in generale un’attinenza maggiore con il brand e, dunque, un concetto da tenere maggiormente in considerazione durante il processo di branding.  </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Lascia liberi gli stakeholder di inserire tutte le parole collegate al brand: valori, idee, persone, etc. Non c’è un limite, anzi, deve essere un processo estremamente libero e rapido. Una volta conclusa l’attività raccogli tutte le parole in un elenco (excel ad esempio) ed inseriscile in un qualunque software per generare tag cloud. Noi suggeriamo <a href="https://monkeylearn.com/word-cloud/" style="color: var(--color-primary)"> <u> monkeylearn </u> </a>
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              avere una visualizzazione rapida e generale di tutti i concetti collegati al brand dal punto di vista degli stakeholder.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            non considerare in assoluto i dati di questo tool, ma usali per ampliare la tua percezione generale sull’immaginario di marca.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/ritrattocinese/">
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
          <b-link class="whiteicon h2" to="/mindmap/">
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

