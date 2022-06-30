<template>
  <div>


    <div>
      <Navbar/>
    </div>

    <div>
      <FirstSection
        title="Un toolkit di Co-design per gestire il tuo progetto di community branding."
        imgSrc="~assets/svg/logo.svg"
      >
        Un Figma pack rivolto ai designer per supportare progetti di
        <b> <a id="tooltipbranding" >
          branding
        </a></b>
        per le community attraverso un toolkit e un framework di Co-design completamente web-based.



        <b-popover target="tooltipbranding" triggers="hover" placement="top" style="tooltiphome">
          <span style="color: #F45A5D; font-size: 16px" > <b> Branding </b> </span>
          ‹brä′ndiṅ› in italiano traducibile
          con “marca”, è l’insieme degli elementi visivi,
          percettivi ed emozionali che vengono associati a
          determinate aziende, organizzazioni, prodotti, servizi o persone.
        </b-popover>

      </FirstSection>



    </div>

    <div>
      <FilledSection
        sottotitolo="Apri un nuovo progetto su Figma, segui gli 8 step del Co-Framework e crea un nuovo brand collaborando con la community."
      >

      Inizia a <i> Co-creare </i>

      </FilledSection>

    </div>

    <div>
      <VideoSectionHome/>
    </div>


    <div>

      <SecondSectionHome

      >

        <i> Co-progetta </i> un brand unico
        che rispecchi al meglio la comunità
        con cui stai collaborando.

      </SecondSectionHome>

    </div>


      <BoxHome/>


<Footer/>

  </div>






</template>

<script>



</script>



<style>

#tooltipbranding:hover{
  color: #F45A5D;
}


</style>
