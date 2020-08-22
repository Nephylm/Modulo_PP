<template>
  <div class=" p-2 p-md-5 col-md-8 text-white rounded cabeza img-fluid" >
    <div class="col-md-5 px-0">
      <h4 class="display-5 font-italic bg-dark">BENEFACTORES FAMILIAS GUADALUPANAS</h4>
    </div>
  </div>
</template>

<script>
export default {
name: "Cabecera"
}
</script>

<style scoped>
.cabeza{
  background-image: url("../Resources/Imagen base.png");
  display:flex;
  text-align: center;
  justify-content: center;
  background-size: contain;
}
.p-2{padding:.5rem!important}
.p-md-5{padding:3rem!important}
.col-md-8{-ms-flex:0 0 66.666667%;flex:0 0 66.666667%;max-width:66.666667%}
.img-fluid{max-width:100%;height:100%}
.rounded{border-radius:.25rem!important}
.text-white{color:#fff!important}
.px-0{padding-right:0!important}
.font-italic{font-style:italic!important}
</style>