<template>



    <b-container class="bv-example-row  risorsetab">
      <b-row>
        <b-col>
          <div>
            Durata attività
          </div>
          <div>
            {{ durata }}
          </div>
        </b-col>
        <b-col>2 of 3</b-col>
        <b-col>3 of 3</b-col>
      </b-row>

    </b-container>



</template>

<script>
export default {
  name: "RisorseTab",
  props: ['durata']
}
</script>

<style scoped>

</style>
