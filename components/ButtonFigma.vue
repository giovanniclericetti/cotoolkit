<template>
  <button type="button" class="btn buttonfigma d-inline-flex">

    <img class="iconfigma ps-3 pt-md-1 " src="~assets/svg/figmaicon.svg">

    <p class="px-3">
      <slot></slot>
    </p>
  </button>
</template>

<script>

export default {
  name: 'ButtonFigma',
}

</script>

<style>

.buttonfigma {
  background-color: white;
  border-radius: 15px;
  height: 42px;
}

.buttonfigma:hover {
  background-color: black;
  color: white;
  transition: 0.3s ease-in-out;
}

.iconfigma {
  height: 25px;
}

@media (max-width: 768px) {
  .buttonfigma {
    background-color: white;
    border-radius: 15px;
    height: 40px;
  }
}

</style>
