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
      title="Moodboard"
      durata="5/20 minuti"
      partecipanti="1/100+ persone"
      tipologia="Asincrono"
      pill1="PERSONALITÀ DI MARCA"
      pill2="IMMAGINI"
      pill3="MOOD"
      pill4="IMMAGINARIO DI MARCA"
      iconrisorsa="r-moodboard"

      >

        È una tavola che raccoglie suggestioni e spunti per restituire l’atmosfera e lo stile di un progetto, di un brand o di un contesto. Questo viene fatto attraverso l’accostamento di immagini diverse che restituiscano ognuna una suggerstione specifica.      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/moodboard.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Partiamo dalla traduzione letterale: “Mood” in inglese vuol dire umore e “board” tavola. La Moodboard è una raccolta di immagini, ma possono anche essere oggetti fisici, che rappresentano in parte o nella sua totalità, in modo diretto o per similitudini e suggestioni, un ambito di interesse; nel nostro caso, un brand. Questo strumento nasce nel mondo del design della moda, ed è estremamente utile per raccogliere le idee e per ispirare te e gli altri.
    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      L’idea è creare una “tavola visiva” mettono insieme elementi diversi che, grazie alle relazioni di senso che intrattengono tra loro, portano a una comprensione di macro e micro aspetti della brand che sarebbero difficili da definire a priori. Questo viene fatto attraverso le immagini, qualunque tipo di immagine, a patto che rispecchi il “mood”, appunto, del brand. Questo tool è molto facile ed utile poichè il nostro cervello è abituato ad interpretare velocemente le immagini. A colpo d’occhio infatti riusciamo a scorgere in un gran numero di immagini connessioni e opportunità che la parola scritta spesso nasconde.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              comprendere meglio e più profondamente tutte le sfaccettature del “mood” del brand, percepito o desiderato dagli utenti.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            selezionare, almeno alla fine dell’attività, dei cluster di immagini o di elementi ricorrenti per definire un mood preciso.          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/mindmap/">
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
          <b-link class="whiteicon h2" to="/onlynessstatement/">
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

