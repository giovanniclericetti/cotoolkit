<template>
<div class="container mb-5">
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
  name: "InfoParagraph",
  props: ['title']

}
</script>

<style scoped>

</style>
