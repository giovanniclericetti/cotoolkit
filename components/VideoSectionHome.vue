<template>

  <div class="container pt-5 mt-5">

  <div class="px-md-5 pt-5 mt-md-5">

    <div>
      <div class="videohome" style="">
        <iframe src="https://player.vimeo.com/video/715180975?h=3471849671" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div>
      <script src="https://player.vimeo.com/api/player.js"></script>

    </div>

  </div>


      </div>



</template>

<script>


</script>

<style>


iframe{
  border-radius: 20px;
  background-color: grey;
  width: 100%;
}

.videohome {
  filter: drop-shadow(0px 4px 8px rgba(10, 10, 10, 0.1));
  padding: 56.25% 0 0 0;
  position:relative;
}

@media (max-width: 768px) {


iframe{
  border-radius: 20px;
  background-color: grey;
  width: 300px;
  height: 800px;
}

}

</style>
