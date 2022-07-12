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
      title="Moduli di invito"
      durata="l'intero progetto"
      partecipanti="1/100+ persone"
      tipologia="testuale"
      pill1="STAKEHOLDER"
      pill2="MEDIA"
      pill3="LINK"
      pill4="PARTECIPAZIONE"
      iconrisorsa="r-moduli"

      >

        Tre template multimediali strutturati per invitare gli stakeholder a prendere parte al progetto e accedere alle diverse attività previste dal framework rendendoli partecipi passo passo dell’evolversi del progetto.
      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/moduli.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      Questi tre strumenti, fortemente intersecati con il framework, hanno scopi diversi in momenti diversi. Il primo modulo ha lo scopo di introdurre il progetto di Co-design e rilasciare il link del questionario. Il secondo serve ad introdurre lo strumento FigJam e invitare gli stakeholder a scolgere le attività del workshop asincrono. Il terzo serve da invito e da sondaggio per schedulare le attività di workshop sincrono.    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Tutti e tre i moduli d’invito hanno come medium primario la mail. Questo favorirà uno svolgimento delle attività da computer e servirà a contattare solo persone realmente interessate a contribuire al progetto. Il primo modulo inoltre ha anche una declinazione social, in particolare Instagram, poichè mira a raggiungere un bacino di utenza più ampio possibile.    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              interfacciarti direttamente con gli stakeholder, comunicare novità e rilasciare link utili allo svolgimento del progetto.            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            modificare ad hoc il testo del template in base alle esigenze progettuali e alle caratteristiche del brand in questione.          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/questionario/">
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
          <b-link class="whiteicon h2" to="/stakeholderanalysis/">
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

