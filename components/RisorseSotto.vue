<template>

  <div class="container-fluid filled justify-content-center px-5 py-5">

      <b-row class="row justify-content-center py-2 py-md-5" align-v="center">

        <b-col md="auto">
          <a class="h2 whiteicon " href="/about">
          <b-icon icon="arrow-left-circle-fill"></b-icon>
        </a>
        </b-col>

        <b-col>

      <p style="color: white">
        Accedi al Figma pack <br>
        e inizia ad usare questo tool
      </p>

    <div>

      <ButtonFigma>
        Accedi al pack
      </ButtonFigma>

    </div>



    </b-col>

        <b-col md="auto">
          <a class="whiteicon h2" href="/about">
            <b-icon icon="arrow-right-circle-fill"></b-icon>
          </a>
        </b-col>

  </b-row>

  </div>

</template>

<script>

export default {
  name: 'FilledSection'
}

</script>

<style>

.filled {
  width: 100vw;
  background-color: var(--color-primary);
  text-align: center;
  color: white;
}

.whiteicon{
  color: white;
}

.whiteicon:hover{
  color: white;
}


</style>
