<template>

  <div class="container-fluid sectionone mt-5 p-5 ">
    <div class="row align-items-center p-5">
      <div class="col-md-7">

          <h2 class="firsttitle mb-4">
            {{title}}
          </h2>

          <p>
            {{sottotitolo}}
          </p>

      </div>

      <div class="col mt-5">

        <img class="gifcover" src="~static/home_section.gif">

      </div>
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

.sectionone{
  height: 100vh;
  width: 100vw;
  background-color: white;
}

.firsttitle{
  font-weight: 700;
  font-size: 45px;
}

.gifcover{
  width: 100%;
}


</style>
