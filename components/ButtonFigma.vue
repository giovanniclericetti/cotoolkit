<template>


  <button type="button" class="btn buttonfigma d-inline-flex m-5">

    <img class="iconfigma ps-3 " src="~static/figmaicon.svg">


    <p class="px-3">
      {{buttontext}}
    </p>

    </div>

  </button>

</template>

<script>

export default {
  name: 'Card',
  props: ['buttontext'],


}

</script>

<style>

.buttonfigma{
  background-color: white;
  border-radius: 15px;
  height: 38px;
}

.buttonfigma:hover{
  background-color: black;
  color: white;
  transition: 0.3s ease-in-out;
}

.iconfigma{
  height: 23px;
}



</style>
