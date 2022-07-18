<template>
  <div class="theme-yellow">


    <div>
      <Navbar/>
    </div>

    <div class="">
      <FirstSection
        title="Un toolkit di Co-design per gestire il tuo progetto di community branding."
        imgSrc="~asssets/svg/logo.svg"
      >
        Un <b> <a id="tooltipfigma" class="parolapop theme-grey">
        Figma pack
      </a></b>  rivolto ai designer per supportare progetti di
        <b> <a id="tooltipbranding" class="parolapop theme-red">
          branding
        </a></b>
        per le  <b> <a id="tooltipcommunity" class="parolapop theme-blue">
        community
      </a></b> attraverso un  <b> <a id="tooltiptoolkit" class="parolapop theme-green">
        toolkit
      </a></b> e un <b> <a id="tooltipframework" class="parolapop theme-grey">
        framework
      </a></b>  di  <i> <b> <a id="tooltipcodesign" class="parolapop">
        Co-design
      </a></b>  </i> completamente web-based.



        <b-popover target="tooltipbranding" triggers="hover" placement="top" class="tooltiphome theme-red">

          <div class="internopop theme-red">

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Branding </b> </span>
            ‹brä′ndiṅ› in italiano traducibile
            con “marca”, è l’insieme degli elementi visivi,
            percettivi ed emozionali che vengono associati a
            determinate aziende, organizzazioni, prodotti, servizi o persone.

          </div>
        </b-popover>

        <b-popover target="tooltipcommunity" triggers="hover" placement="right" class="tooltiphome">

          <div class="internopop theme-blue">

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Community </b> </span>
             ‹këmi̯ùuniti› insieme di persone che, mosse dal comune interesse nei confronti di un argomento, condividono informazioni su di esso sfruttando vari strumenti che la tecnologia mette loro a disposizione.

          </div>
        </b-popover>

        <b-popover target="tooltiptoolkit" triggers="hover" placement="top" class="tooltiphome">

          <div class="internopop theme-green">

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Toolkit </b> </span>
             ‹ˈtuːlkɪt› letteralmente “cassetta degli attrezzi”, è una collezione di strumenti (tool) da usare in combinazione per raggiungere uno scopo specifico. Questi strumenti posso essere fisici o digitali, semplici, come un post it, o complessi, come un framework.
          </div>
        </b-popover>

        <b-popover target="tooltipcodesign" triggers="hover" placement="top" class="tooltiphome">

          <div class="internopop theme-yellow">

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Co-design </b> </span>
             ‹ˌkəʊdɪˈzaɪn› si riferisce allo sforzo creativo-progettuale di combinare più visioni, input e competenze di persone diverse, designer e non, per risolvere uno specifico problema comune.

          </div>
        </b-popover>

        <b-popover target="tooltipfigma" triggers="hover" placement="right" class="tooltiphome">

          <div class="internopop theme-grey">

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Figma pack </b> </span> è l’insieme di elementi e tool
            raccolti e organizzati in un unico file Figma progettati con un preciso scopo. <br> <br>

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Figma </b> </span>
             è una piattaforma online che facilita
            il processo creativo e la prototipazione
            di un servizio sfruttando tool collaborativi.



          </div>
        </b-popover>

        <b-popover target="tooltipframework" triggers="hover" placement="right" class="tooltiphome">

          <div class="internopop theme-grey">

            <span style="  color: var(--color-primary);; font-size: 16px" > <b> Framework </b> </span>
             ‹ˈfrāmˌwərk› in italiano “quadro strutturale” serve a definire una struttura ideale, una sequenza di azioni, una serie di regole. Il Design Framework è una struttura che regola un progetto di design definendo tempi e modi di azione.
          </div>
        </b-popover>

      </FirstSection>



    </div>

    <div id="portaquifreccia">
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


      <BoxHome class="mb-5"/>

    <div  class="theme-purple">
      <DownloadHandbook
        sottotitolo="Scopri la ricerca che sta dietro a questo progetto"
      >

        Scarica il report

      </DownloadHandbook>

    </div>

<Footer/>

  </div>






</template>

<script>



</script>



<style>

#tooltipbranding:hover{
  color: var(--color-primary);
}

.internopop{
  border: none;
  font-size: 16px;
}

.parolapop{
  color: #7D7D7D;
}

.parolapop:hover{
  cursor: pointer;
  color: var(--color-primary);

}



</style>
