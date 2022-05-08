<template>

  <div class="ciao">
    <h2> bella bro </h2>
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

.ciao{
  background-color: red;
}

</style>
