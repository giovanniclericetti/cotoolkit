<template>
<div class="container mb-5">
  <h3 class="mb-4">
    {{ title }}
  </h3>

  <p>
    <slot/>
  </p>

</div>

</template>

<script>

export default {
  name: "InfoParagraph",
  props: ['title']

}
</script>

<style scoped>

</style>
