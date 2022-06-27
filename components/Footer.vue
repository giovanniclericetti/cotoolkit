<template>

  <div class="container-fluid footer justify-content-center p-5">


      <b-row class="justify-content-md-center row" align-v="center">

        <b-col md="2" class="px-4 py-2 footerseparation" >

          <img src="~assets/svg/iconfooter.svg" alt=""  height="40px" class="d-inline-block align-text-top ">



        </b-col>

        <b-col md="auto">


            <b-row class="justify-content-md-center px-5" >

              <b-col md="auto">
                <div class="footer_container px-5">
                  <div>
                    <b> Created by </b>
                  </div>
                  <a href="https://www.instagram.com/marcobort/">
                    @marcobort
                  </a>
                </div>
              </b-col>

              <b-col md="auto">
                <div class="footer_container px-5">
                  <div>
                    <b> Contact us </b>
                  </div>
                  <a href= "mailto:cotoolkit@gmail.com">
                    cotoolkit@gmail.com
                  </a>
                </div>
              </b-col>

              <b-col md="auto">
                <div class="footer_container px-5">
                  <div>
                    <b> Project </b>
                  </div>
                  <div>
                    open source powered by Figma
                  </div>
                </div>
              </b-col>

            </b-row>


        </b-col>

        <b-col md="auto" class="p-5 py-0 footerseparation2  d-none d-lg-block" style="text-align: left">

          <div class="mx-5">
          <div>
            <b> Figma Pack </b>
          </div>

          <div class="mt-1" >

            <button type="button" class="btn buttonfigmareduct d-inline-flex">

              <img class="iconfigmareduct"  src="~assets/svg/figmaicon.svg">

              <p class="px-1" style="font-size: 10px">
                Accedi al pack
              </p>
            </button>
          </div>
          </div>
        </b-col>
      </b-row>

  </div>
</template>

<script>

export default {
  name: "Footer",

}


</script>

<style scoped>

.footer{
  background-color: #272D31;
  color: white;
  text-align: center;
  width: 100vw;
}

.footer_container{
  font-size: 16px;
  text-align: left;
}

a {
  color: white;
}

.footerseparation{
  border-right: 2px white solid;
  height: 60px;
}

.footerseparation2{
  border-left: 2px white solid;
  height: 60px;
}

.iconfigmareduct {
  height: 16px;
}

.buttonfigmareduct {
  background-color: white;
  border-radius: 7px;
  height: 28px;
}


</style>
