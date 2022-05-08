<template>

  <div class="container-fluid filled justify-content-center p-5">


          <h2 class="firsttitle my-4 mt-5">
            {{title}}
          </h2>

    <div class="row justify-content-center">
          <p class=" subtitle ">
            {{sottotitolo}}
          </p>

    </div>

    <div>
      <ButtonFigma
        buttontext="Accedi al Pack"
      />
    </div>


      </div>



</template>

<script>

export default {
  name: 'Card',
  props: ['title', 'imgSrc', 'chisono', 'sottotitolo'],
  data() {
    return {
      showParagraph: true
    }
  },
  methods: {
    onClickButton() {
      console.log("mi hai premuto");
      this.showParagraph = false
    }
  }
}

</script>

<style>

.filled{
  width: 100vw;
  background-color: #FCBB16;
  text-align: center;
  color: white;
}

.firsttitle{
  font-weight: 700;
  font-size: 45px;
}

.subtitle{
  max-width: 520px;
}



</style>
