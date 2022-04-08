<template>
  <div class="">

    <h2>Titolo home page</h2>
    <div >
      <Card title="titolo della card" />
      <Card title="titolo della card 2" imgSrc="https://avatars.githubusercontent.com/u/43304601?v=4" chisono="ciao, io sono michiburno"/>
      <Card title="titolo della card 3" imgSrc="https://avatars.githubusercontent.com/u/77500466?v=4" chisono="ciao, io sono giocle"/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      cards: [
      {
        title: 'Card1'
      },
      {title: 'Card2'},
      {title:'Card3'}
      ]
    };
  }
}

//per renderlo variabile o DUE GRAFFE per testo o DUE PUNTI davanti attirbuto

</script>
