<template xmlns="http://www.w3.org/1999/html">
<div class="container bg-primary">

  <b-row align-v="stretch" style="height: 450px">

    <b-col cols="8">
      <BoxHomeFramework/>
    </b-col>

    <b-col cols="4" >
      <BoxHomeCoDesign/>
    </b-col>

  </b-row>

  <b-row align-v="stretch" class="my-4" style="height: 600px">

    <b-col cols="4">
      <BoxHomeTool/>
    </b-col>

    <b-col cols="4">
      <BoxHomeProject/>
    </b-col>

    <b-col cols="4">
      <BoxHomeFigma/>
      <BoxHomePreferiti/>
    </b-col>

  </b-row>


  </div>

</template>

<script>
export default {
  name: "BoxHome"
}
</script>

<style scoped>

r{

  background-color: #F9F9F9;
  border-radius: 30px;
  font-size: 18px;
  text-align: center;
}

</style>
