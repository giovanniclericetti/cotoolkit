<template>

  <div class="container my-5 pt-md-5">

    <h4 class="mb-4">
      {{ title }}
    </h4>

    <p>
      <slot/>
    </p>

  </div>

</template>

<script>
export default {
  name: "RisorseSection",
  components: {},
  props: ['title'],
}


</script>

<style scoped>

</style>
