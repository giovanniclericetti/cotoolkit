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
      title="How Might We"
      durata="20/40 minuti"
      partecipanti="2/20 persone"
      tipologia="Sincrono"
      pill1="STAKEHOLDER"
      pill2="CLUSTER"
      pill3="SCELTE"
      pill4="PESO DECISIONALE"
      iconrisorsa="r-howmight"

      >

        Una volta definiti i punti critici ed i problemi di un progetto è utile riformularli sotto forma di domande “How Might We” per trasformare queste sfide in opportunità, non per una soluzione specifica, ma come cornice per favorire il pensiero innovativo.      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/how.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Lo sviluppo di domande trigger da approfondimenti e storie degli utenti è un buon modo per convertire la ricerca in un'ampia gamma di idee attuabili. Usa questo metodo quando hai una buona ricerca o esperienza su cui basarti, o quando hai bisogno di fare un passo indietro rispetto alle idee e tornare ai bisogni e alle opportunità che ci stanno dietro. How Might We​ è una delle metodologie utilizzate dal ​Design Thinking​ per generare, attraverso brevi domande, un brainstorming capace di amplificare la creatività per risolvere questi problemi o ampliarne la percezione in un contesto più ampio.    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Inizia osservando le dichiarazioni di insight/problem che hai creato. Prova a riformularle come domande aggiungendo "Come potremmo.." all'inizio. L'obiettivo è trovare opportunità per il design, quindi se le tue intuizioni suggeriscono diverse domande su How Might We, è meglio. Infine, assicurati che il tuo How Might We's non sia troppo ampio.  È un processo complicato ma un buon How Might dovrebbe garantire una cornice sufficientemente stretta per farti sapere da dove iniziare il tuo brainstorming.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              trovare soluzioni alternative a problemi già definiti in precedenza ribaltando il punto di vista, da problema ad opportunità.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            definire domande HMW abbastanza ampie da garantire molteplici risposte ma non troppo da non inquadrare un problema.
          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/roleplaying/">
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
          <b-link class="whiteicon h2" to="/crazy8/">
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

