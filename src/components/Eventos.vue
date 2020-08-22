<template>
  <b-container >
    <div class=" align-items-center ">
        <b-row class="justify-content-md-center">
          <b-col>
            <div class="card mb-4 shadow-sm">

              <div class="embed-responsive embed-responsive-4by3">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/QG_ewvGeXGE" frameBorder="0"
                        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                        allowFullScreen></iframe>
              </div>
              <div class="card-body">
                <p class="card-text">Descripción.
                  Parroquia Inmaculada Concepción Clavería está por
                  construir un comedor de caridad para poder servir 120
                  comidas diarias a la población en situación de calle. </p>
                <div class="d-flex justify-content-between align-items-center">

                </div>
              </div>
            </div>
          </b-col>
          <b-col col lg="1"></b-col>
          <b-col>
            <img class="img-fluid" src="https://www.diariodemexico.com/sites/default/files/field/image/beneficiencia.jpg"  width="400"
                 height="241" />
            <div class="card-body">
              <h5 class="card-text">Descripcion. </h5>
            </div>
          </b-col>

        </b-row>


    </div>
  </b-container>

</template>

<script>
export default {
  name: "Eventos"
}
</script>

<style scoped>
.card{position:relative;display:-ms-flexbox;display:flex;-ms-flex-direction:column;flex-direction:column;min-width:0;word-wrap:break-word;background-color:#fff;background-clip:border-box;border:1px solid rgba(0,0,0,.125);border-radius:.25rem}
.d-flex{display:-ms-flexbox!important;display:flex!important}
.justify-content-between{-ms-flex-pack:justify!important;justify-content:space-between!important}
.align-items-center{-ms-flex-align:center!important;align-items:center!important}
.col-md-5{-ms-flex:0 0 41.666667%;flex:0 0 41.666667%;max-width:41.666667%}
.shadow-sm{box-shadow:0 .125rem .25rem rgba(0,0,0,.075)!important}
.embed-responsive{position:relative;display:block;width:100%;padding:0;overflow:hidden}
.embed-responsive-4by3::before{padding-top:75%}
.card-body{-ms-flex:1 1 auto;flex:1 1 auto;padding:1.25rem}
.card-text:last-child{margin-bottom:0}
</style>