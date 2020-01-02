<template>
  <div id="app">
    <center>
      <img alt="Vue logo" src="./assets/logo.png"><br>
      <contador/>
      <contador/>
      <contador/>
      <contador/>
      <contador/>
      <contador/>
      <contador/> <br>
      <h2>Listado de planes de Cursos de Programacion</h2>
      <div class="planes">
        <!-- <div class="plan">
          <div class="descripcion">
            <span class='titulo'>Plan 1 - Principiantes</span>
          </div>
        </div>

        <div class="plan">
          <div class="descripcion">
            <span class='titulo'>Plan 2 - Intermedio</span>
          </div>
        </div>

        <div class="plan">
          <div class="descripcion">
            <span class='titulo'>Plan 3 - Avanzado</span>
          </div>
        </div>
        <plan nombre="Plan 1 - Principiantes"/>
        <plan nombre="Plan 2 - Intermedio"/>
        <plan nombre="Plan 3 - Avanzado"/>
        <plan nombre="Plan 4 - Hackers"/>
        <plan/>
                    -->

        <planes/>




      </div>
    </center>
  </div>
</template>

<script>
  import Contador from './components/Contador.vue'
  import Planes from './components/Planes.vue'

  export default {
    name: 'app',
    components: {
      Contador,
      Planes
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
  }



</style>
