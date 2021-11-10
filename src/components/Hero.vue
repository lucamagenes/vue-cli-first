<template>
  <div class="jumbotron">
      <img alt="jumbotron image" src="../assets/wallpaperflare.jpg">
      <div class="container">
          <h1>Fluid jumbotron</h1>
          <p>This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'hero',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotron{
    width: 100%;
    height: calc(100vh - 60px - 74px);
    position: relative;
}
img{
    width: 100%;
    height: 100%;
}
.container{
  position: absolute;
  bottom: 50px;
  left: 50px;
  color: white;
  text-align: left;
  font-size: 25px;
  font-weight: bold;
}

</style>
