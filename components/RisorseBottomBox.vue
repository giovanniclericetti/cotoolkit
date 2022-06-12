<template>

  <div class="container risorsetab box p-5">

    <h5 class="titlebox">
      {{ title }}
    </h5>

    <p>
      <slot/>
    </p>

  </div>


</template>

<script>
export default {
  name: "RisorseBottomBox",
  props: ['title']
}
</script>

<style scoped>

.titlebox{
  color: #FCBB16;
  font-weight: bold;
}

.box{
  text-align: left;
}

</style>
