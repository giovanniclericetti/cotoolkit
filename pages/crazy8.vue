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
      title="Crazy 8"
      durata="8 minuti"
      partecipanti="2/20 persone"
      tipologia="Sincrono"
      pill1="LOGO"
      pill2="SKETCH"
      pill3="IDEE"
      pill4="SPRINT DESIGN"
      iconrisorsa="r-crazy"

      >

        È un esercizio di “Sprint Design” che sfida le persone a disegnare otto idee distinte in otto minuti. L'obiettivo è spingersi oltre la prima idea, spesso la meno innovativa, e generare un'ampia varietà di soluzioni per il problema che stai affrontando.      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/stakeholder.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      I membri del gruppo senza background di progettazione potrebbero inizialmente trovare questo metodo intimidatorio, quindi è utile rassicurare tutti sul fatto che si tratta di schizzi approssimativi. Non devono essere perfetti o belli: gli schizzi devono solo comunicare l'idea. È anche importante ricordare che le idee non devono essere grandiose ma devono provare a rispondere in modo semplice a problemi spesso complessi. Questo esercizio mira a dare spazio ai nostri impulsi creativi basilari in modo veloce ed immediato.   </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Ogni membro del team piega il proprio pezzo di carta in otto sezioni. Una volta impostato il timer su 8 minuti, si inizia. Individualmente, ogni membro del team abbozza un'idea in ogni rettangolo, facendo del proprio meglio fino a riempire tutte le sezioni. Quando il timer si spegne, tutte le penne vengono poggiate e si inizia a presentare e a confrontarsi sulle idee e su cosa si volesse esprimere nel disegno.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              abbozzare idee di logo sulla base di cosa si aspettano gli stakeholder e cosa fa parte del loro immaginario.            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            fare in modo che nel tempo prestabilito ognuno riempia tutti gli 8 spazi, anche con sketch apparentemente inutili.          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/howmightwe/">
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
          <b-link class="whiteicon h2" to="/co-framework/">
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

