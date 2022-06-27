<template>

  <div class="container bg-primary" >


    <img :src="require(`~/assets/svg/${svghover}.svg`)" />


  </div>

</template>

<script>
import ScrollArrow from "assets/svg/provauno.svg";
import ProvaSvg1 from "assets/svg/frecciahover.svg";

export default {
  name: "BoxHover",
  components: {},
  props: ['svghover'],
}
</script>

<style scoped>



</style>
