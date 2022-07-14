<template xmlns="http://www.w3.org/1999/html">
<div class="container">

<div class="desktop">

  <b-row align-v="stretch" style="height: 450px">

    <b-col cols="8"> <b-link class="linkino" to="/co-framework/">
      <BoxHomeFramework/> </b-link>
    </b-col>

    <b-col cols="4" >
      <b-link class="linkino" to="/handbook/">
      <BoxHomeCoDesign/> </b-link>
    </b-col>

  </b-row>

  <b-row  class="my-4" style="height: 530px">

    <b-col cols="4"> <b-link class="linkino" to="/risorse/">
      <BoxHomeTool/>
    </b-link>
    </b-col>

    <b-col cols="4"> <b-link class="linkino" to="/about/">
      <BoxHomeProject/>    </b-link>
    </b-col>

    <b-col cols="4" align-v="stretch">

      <b-link class="linkino" href= "https://www.figma.com">
      <BoxHomeFigma class="mb-4"/>    </b-link>
      <b-link class="linkino" href= "mailto:cotoolkit@gmail.com"> <BoxHomePreferiti/> </b-link>



    </b-col>

  </b-row>

</div>


  <div class="mobile mb-5">

    <b-row>

      <b-col class="m-2">

        <b-link class="linkino" href= "mailto:cotoolkit@gmail.com" align-v="stretch">
          <BoxHomeFramework/>
        </b-link>

      </b-col>



      <b-col class="m-2" >

        <b-link class="linkino"  align-v="stretch">
          <BoxHomeCoDesign/>
        </b-link>

      </b-col>

      <b-col class="m-2">

        <b-link class="linkino" href= "mailto:cotoolkit@gmail.com" align-v="stretch">
          <BoxHomeTool/>
        </b-link>

      </b-col>

      <b-col class="m-2">

        <b-link class="linkino"  align-v="stretch">
          <BoxHomeProject/>
        </b-link>
      </b-col>

      <b-col class="m-2">

        <b-link class="linkino" href= "https://www.figma.com">
          <BoxHomeFigma />    </b-link>

      </b-col>

      <b-col class="m-2">

        <b-link class="linkino" href= "mailto:cotoolkit@gmail.com" align-v="stretch">
          <BoxHomePreferiti/>
        </b-link>

      </b-col>





    </b-row>



  </div>

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

.linkino{
  color: black;
}



</style>
