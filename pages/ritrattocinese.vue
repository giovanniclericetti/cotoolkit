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
      title="Ritratto Cinese"
      durata="5/10 minuti"
      partecipanti="1 persona"
      tipologia="per il designer"
      pill1="PERSONALITÀ DI MARCA"
      pill2="PALETTE"
      pill3="MOOD"
      pill4="IMMAGINARIO DI MARCA"

      iconrisorsa="r-ritratto">

        Questo strumento è utile per raccogliere indizi sulla personalità della marca. Attraverso la proiezione del brand su elementi esterni ad esso, gli stakeholder dettano un immaginario di marca che lavora per similitudini.
      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/ritratto.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Il ritratto cinese è un esercizio individuale e di gruppo, in cui i partecipanti collezionano le loro proiezioni mentali, le immagini che vengono loro suscitate dal paragonare l’oggetto dello studio e dell’esercizio a diverse altre entità: vegetale, animale, sport, pietanza, etc. Lo scopo dell’esercizio è quello di permettere la raccolta di informazioni sintetiche, visive o testuali, su come il brand viene percepito e quali sono gli elementi a cui gli utenti pensano quando parlano della marca.    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      L’attività è piuttosto semplice. Sulla base di un template di 9 quadranti, ognuno impone un paragone
      “E se fosse un...quale sarebbe?”. Agli stakeholder viene chiesto di inserire sotto forma di immagine o di testo l’elemento che ritengono più adeguato in relazione al brand. Una volta conclusa l’attività, bisogna ricercare pattern ricorrenti (stesso colore, stesse vibes, etc.) per definire quali elementi è opportuno trasporre sulla nuova identità di marca.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              comprendere come è percepita la marca, che immaginario la circonda e se ci sono elementi iconici ricorrenti.            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            usare la formula: “e se fosse...” proponendo una decina di parallelismi: immediati e utili a te per definire un quadro di marca.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/stakeholderanalysis/">
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
          <b-link class="whiteicon h2" to="/tagcloud/">
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

