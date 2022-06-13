<template>

  <div>
      <h3 class="mb-4">
        {{ title }}
      </h3>


      <h7>
        <slot/>
      </h7>

  </div>


</template>

<script>
export default {
  name: "BoxHover",
  components: {},
  props: ['title'],
}


</script>

<style scoped>

</style>
