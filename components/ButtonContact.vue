<template>
  <button type="button" class="btn buttoncontact shadow theme-purple">

    <p class="px-4">
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

.buttoncontact {
  background-color: white;
  border-radius: 15px;
  height: 42px;
}

.buttoncontact:hover {
  background-color: var(--color-primary);
  color: white;
  transition: 0.3s ease-in-out;
}



</style>
