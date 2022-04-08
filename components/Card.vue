<template>

  <div class="card">
    <h2 :class="title">{{title}}</h2>

    <p v-if="showParagraph">
      Questa è una card

      <button type="button" name="button" @click="onClickButton">Premimi per nascondermi</button>

    </p>
    <img :src="imgSrc">
    <h5>{{chisono}}</h5>
  </div>
</template>

<script>
  export default {
    name: 'Card',
    props: ['title', 'imgSrc', 'chisono'],
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

<style scoped>
  h2 {
    color: red
  }
</style>
