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
      title="Role Playing"
      durata="30 minuti"
      partecipanti="2/20 persone"
      tipologia="Sincrono"
      pill1="PUNTI DI FORZA"
      pill2="KEYWORDS"
      pill3="PERSONAGGI"
      pill4="TOUCHPOINTS"
      iconrisorsa="r-role"

      >

        È uno strumento veloce ed affidabile che gestisce i cluster di utenti in base a due parametri: il potere e l’interesse. Il potere di uno stakeholder definisce quanto questo possa influenzare le varie decisioni prese riguardo il progetto. Il fattore “interesse” invece si basa sull’impatto che le decisioni progettuali prese avranno sull'esperienza dell’utente.
      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/role.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Il role play è una tecnica di rappresentazione spesso utilizzata durante le sessioni di co-design; permette di spiegare un'idea di servizio o di prodotto recitando uno scenario esemplificativo di utilizzo. Il gioco di ruolo in genere richiede la definizione di alcuni ruoli (ad esempio l'utente, il dipendente del servizio, ecc.) e la preparazione di prototipi grezzi o altri materiali che possono facilitare la performance. Mentre una squadra recita la propria storia, il resto del pubblico viene a conoscenza dell'idea e del contesto di riferimento.

    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Ci si divide in due gruppi o squadre, o semplicemente si scelgono due o più persone che interpretino dei ruoli. Si dà del tempo alle persone per prepararsi fornendo elementi su cui lavorare come prototipi o parole di riferimento. Finita la preparazione, si espone la storia: in particolare, per il Role Playng in ambito branding lo scopo è convincere gli altri partecipanti della bontà della marca fino al punto di persuaderli ad acquistare, partecipare o entrare a far parte della community, in opposizione a “personaggi” che hanno lo scopo di trovare difetti e screditare la brand reputation, creando una situazione di opposizione.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              trovare la ragioni profonde di partecipazione al brand, punti di forza, debolezza e touchpoint tra brand e community.            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            lasciare del tempo di preparazione alle “squadre” fornendo dei punti di partenza, come ad esempio delle parole.          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/definizionevalori/">
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
          <b-link class="whiteicon h2" to="/howmightwe/">
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

