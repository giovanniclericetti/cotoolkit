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
      title="Onlyness Statement"
      durata="5/5 minuti"
      partecipanti="1/100+ persone"
      tipologia="Asincrono"
      pill1="BRAND PURPOSE"
      pill2="UNICITÀ"

      iconrisorsa="r-onlyness"

      >

        È una descrizione breve e concisa dell’essenza della marca e dei fattori che possono diversificarla e renderla preferibile rispetto ai competitor. Questo strumento è utile per riassumere la Brand Purpose partendo dall’esperienza diretta degli stakeholder.      </RisorseIntro>




<b-row class="my-5 pt-md-5 justify-content-center">

  <b-col class="col-12 row m-mb-5" order="3" order-md="1">

    <img style="width:100%" src="~assets/images/onlyness.png" >

  </b-col>

  <b-col class="col-12 mt-md-5" order="1">

    <InfoParagraph
      title="Che cos’è?" >

      L’Onlyness Statement (dichiarazione di unicità) è una tecnica di posizionamento sviluppata nel campo del marketing dal brand strategist Marty Neumeier. L'idea principale è che un brand è competitivo sul mercato, dunque è strategicamente posizionato, quando è "l'unico" nel fare o nell’essere qualcosa in una categoria specifica o in area di mercato. Questa breve frase riassuntiva torna molto utile per comprendere cosa rende unica e dunque attrattiva la marca.    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Sfruttando un template testuale che ruota attorno a quelle che sono conosciute come “W Questions” (Cosa? Quando? Come? Chi? Perchè? Dove?), gli stakeholder devono completare gli spazi vuoti andando a definire ciò che per ciascuno definisce meglio la marca. Partendo da questi “contributi”, in un secondo memento bisogna strutturare una frase unitaria per definire al meglio il fattore di unicità della marca.
    </InfoParagraph>

</b-col>



</b-row>



      <div class="mb-md-5 mb-5 pb-md-5">
        <b-row>

          <b-col class="mb-md-5 mb-3 col-12 col-md-6">
            <RisorseBottomBox title="Usalo per">
              definire cosa rende “speciale” il brand, strutturando una catch phrase che potrai riutilizzare in seguito nel progetto.             </RisorseBottomBox>
          </b-col>

          <b-col class="mb-md-5 md-3 col-12 col-md-6">
          <RisorseBottomBox title="Ricordati di">
            riadattare i contributi degli stakeholder in una frase riassuntiva dei concetti fondanti del brand.          </RisorseBottomBox> </b-col>

        </b-row>

      </div>



    </div>


    <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col class="col-1">
          <b-link class="h2 whiteicon " to="/moodboard/">
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
          <b-link class="whiteicon h2" to="/definizionevalori/">
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

