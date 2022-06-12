<template>






  <div>
    <Navbar/>

<a class="indietro h2" href="/about">
    <b-icon icon="arrow-left-short"></b-icon>
</a>

    <div class="container">

      <RisorseIntro
      imgSrcIcon="~assets/svg/about_figmapack.svg"
      title="Co-Framework"
      durata="l'intero progetto"
      partecipanti="1 persona"
      tipologia="per il designer"
      >

        Un design framework è una struttura reiterabile espressa in forma visiva che aiuta a organizzare le informazioni e le idee di un problema o la sequenza esecutiva di un progetto, in modo da poterci lavorare in modo più efficace.

      </RisorseIntro>

      <div class="row justify-content-center screencontainer mx-auto">

        <img src="~assets/images/co-framework-screen.png" >

      </div>


<div class="my-5 pb-5">
    <InfoParagraph
      title="Che cos’è?" >

      Un framework è spesso composto da un elenco pertinente di categorie sequenziate secondo uno specifico ordine con lo scopo di aiutare il progettista a strutturare attività in modo guidato e pre-progettato, per ottimizzare al meglio le risorse e facilitare la meta-progettazione. Spesso per facilitarne la comprensione si realizzano grafici sintetici che riassumano il framework in step. Affinchè un framework sia funzionale, inoltre, deve poter essere reiterabile, dunque adattabile a più di un progetto nel medesimo ambito.

    </InfoParagraph>

    <InfoParagraph
      title="Come si usa?">

      Per “usare” un framework basta seguire le istruzioni che questo impone, seguendo passo passo le attività e le modalità proposte dal framework e lasciandosi guidare nei tempi e nei modi del progetto.
      Per comprendere lo scopo e gli step di un framework dovrebbe bastare la presa visione della sua rappresentazione schematica, mentre per comprenderne i meccanismi e poterlo applicare correttamente, tendenzialmente, servirà un approccio più immersivo di lettura o visualizzazione dei contenuti proposti.

    </InfoParagraph>
</div>

      <div class="mb-5 pb-5">
        <b-row>

          <b-col class="mb-5">
            <RisorseBottomBox title="Usalo per">
              informarti sul Co-design e sulle sue pratiche, imparando a progettare seguendo i criteri dei questo modello.
            </RisorseBottomBox>
          </b-col>

          <b-col class="mb-5">
          <RisorseBottomBox title="Ricordati di">
            implementare nella pratica gli aspetti teorici contenuti all’interno dell’handbook, avendo sempre un approccio democratico.          </RisorseBottomBox>
          </b-col>

        </b-row>

      </div>



    </div>


    <RisorseSotto/>

    <Footer/>

  </div>



</template>

<script>

export default {
  name: 'AboutPage'
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

