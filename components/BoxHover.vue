<template>

  <div class="mb-md-2 mt-md-3 testohoveratolink scrittebox" >

    {{risorsa}}


  </div>

</template>

<script>

export default {
  name: "BoxHover",
  components: {},
  props: ['risorsa', 'svghover'],
}
</script>

<style scoped>

@media (max-width: 768px) {
.scrittebox {
 font-size: 14px;
  line-height: 110%;
  padding-top: 5px;
  }}
</style>
