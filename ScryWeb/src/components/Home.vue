<template>
<div class="container-fluid m-0 p-0">

    <div id="main" class="full-height bg-danger p-4">
      <div class="container pt-3">

        <div class="row pb-5">
          <div class="col-lg-3">
          </div>

          <div class="col-lg-6">
            <img id="logo" src="../assets/lclogo.png" class="img-fluig">
          </div>

          <div class="col-lg-3">

          </div>

          </div>

      </div>

    </div>

    <div id="row2" class="bg-dark p-3">

    </div>

</div>
</template>

<script>
export default {
  data () {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #main {
    background-color: rgb(117, 28, 219);
    background: url('../assets/bg_trees.png') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}

#logo {
  max-height: 50vh;
}
</style>
