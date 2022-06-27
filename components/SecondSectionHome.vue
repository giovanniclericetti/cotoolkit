<template>

  <div class="container m-0">

    <div class="row justify-content-center sectionconforme align-items-center">

      <h2 class="text-center co-progetta py-5 mt-5">
        <slot/>
      </h2>




    </div>

      </div>



</template>

<script>

export default {
  name: 'SecondSectionHome',
  props: ['title'],

}

</script>

<style>


.co-progetta{
  max-width: 1000px;
}

.sectionconforme{
  width: 100vw;
  height: 700px;
  background-position: center;
  background-image: url("~static/formegruppo.svg");
  background-repeat: no-repeat;
  background-size: cover;

}


</style>
