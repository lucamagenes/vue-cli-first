<template>
  <div class="jumbo">
    <div class="jumbotron">
        <img alt="jumbotron image" src="../assets/wallpaperflare.jpg">
        <div class="container">
            <h1 class="display-4">Fluid jumbotron</h1>
            <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
        </div>
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
    height: calc(100vh - 104px)
}
img{
    width: 100%;
    height: 100%;
}
</style>
