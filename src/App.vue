<template>
  <div id="app" class="App-header" >
    <b-container fluid="sm">
      <b-row class="justify-content-center">
        <b-col></b-col>
        <b-col cols="11"><Cabecera/></b-col>
        <b-col></b-col>

      </b-row>
    </b-container>

    <div class="col-md-12">
      <div class="row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col-auto d-none d-lg-block mt-7">
          <h1 style="color: white">A</h1>
          <img class="rounded-circle mr-2 ml-4" src="https://elobservadorenlinea.com/wp-content/uploads/2018/06/alarcon1.jpg" align="center" width="300" height="300">
        </div>
        <div class="col p-3 d-flex flex-column position-static">
          <strong class="d-inline-block mb-2 text-primary">P. JESÚS PEDRO ALARCÓN MÉNDEZ</strong>
          <div class="mb-1 text-muted">
            <p class="card-text mb-auto text-justify">Originario de La Ciudad de México. Mis padres me acercaron desde pequeño al Santuario de la
              Morenita donde aprendí a ver la mano de Dios reflejada en el amor de la Guadalupana y a
              agradecerle y a consagrarme a ella. Hice mi profesión como Marista para la Sociedad de María
              en 1980 y fui ordenado sacerdote en 1988. Cursé estudios de teología en Milltown Park, Dublín.
              Inicié la licencia en Espiritualidad en la Pontificia Universidad Gregoriana en Roma y la concluí
              en la Pontificia Universidad de México. Realicé el doctorado en la Facultad Jesuita de Belo Horizonte en Brasil.
              Encargado por mis superiores he contribuido en la formación sacerdotal marista de nuestros estudiantes en México,
              Brasil y ahora en Roma</p>
          </div>
          <div class="mb-1 text-muted">
            <p class="card-text mb-0 text-center font-weight-bold">Libro escrito: El Amor De Jesús Vivo En La Virgen De Guadalupe</p>
            <p class="card-text mb-0 text-center font-weight-bold">Si desea adquiri el libro puede accder al siguiente enlace:</p>
            <a class="btn btn-primary mt-2" href="https://es.scribd.com/book/384159442/El-Amor-De-Jesus-Vivo-En-La- Virgen-De-Guadalupe" role="button">Link de adquisición</a>
          </div>
        </div>
      </div>
    </div>
    <b-container>
      <Misas_y_Homilias/>
    </b-container>
    <b-container>
      <Eventos/>
    </b-container>
    <Foot/>
  </div>

</template>

<script>
import Cabecera from "@/components/Cabecera";
import Misas_y_Homilias from "@/components/Misas y Homilias"
import Foot from "@/components/Foot";
import Eventos from "@/components/Eventos";


export default {
  name: 'App',
  components: {
    Eventos,
    Foot,
    Misas_y_Homilias,
    Cabecera
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  justify-content: center;
  color: #2c3e50;
  margin-top: 10px;

}
.App-header {

  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: calc(10px + 2vmin);
  color: white;
}
.col-md-12{-ms-flex:0 0 100%;flex:0 0 100%;max-width:100%}
</style>
