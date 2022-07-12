<template>

  <div class="container risorsebox box p-2 p-md-5">

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
  color: var(--color-primary);
  font-weight: bold;
}

.box{
  text-align: left;
}

.risorsebox{
  background-color: #F9F9F9;
  width: 90%;
  border-radius: 20px;
  text-align: left;
  min-height: 240px;
  box-shadow: 0px 0px 12px rgba(0, 0, 0, 0.12);
}

@media (max-width: 768px) {

  .risorsebox{
  background-color: white;
  width: 100%;
    min-height: 50px;
  text-align: left;
  box-shadow: none;}
}

</style>
