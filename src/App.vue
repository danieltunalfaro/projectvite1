<script setup lang="ts">
import HeaderComponent from './components/HeaderComponent.vue'
const myId = "coffe"
let myCondition = false
let condition2 = false

const movies = ["Lord of the Rings", "Star Wars", "Dune", "Batman"]

</script>


<template>

  <div id="principal" class="pagina">
    <HeaderComponent />

    <div class="presentacion">
      <h1 class="title":class="myCondition ? 'highlight' : 'white'">
        Formación profesional
      </h1>
    </div>

    <main id="contenido" class="contenido">

      <div class="informacion">
        <h2>Sobre mí</h2>
        <p>
          Mi nombre es Daniel Emmanuel Tun Alfaro, tengo 26 años y pertenezco a la carrera
          de Administración de Tecnologías de la Información cursando en
          5to semestre y pienso enfocarme en el manejo de servidores.
        </p>
      </div>

      <div class="materias">
        <h2>Materias que más me han interesado</h2>
        <ul>
          <li>Programación</li>
          <li>Redes</li>
          <li>Servidores comerciales</li>
        </ul>
      </div>

      <div class="habilidades">
        <h2>Habilidades</h2>
        <ul>
          <li>Programación en Java, Python, C++</li>
          <li>Administración de servidores Windows</li>
          <li>Administración de redes</li>
        </ul>
      </div>
       
    </main>

    <footer id="pie" class="pie">
      <h3>Contactos</h3>
      <p>
        danieltunalfaro@gmail.com
      </p>
      <p>
        9997-48-53-66
      </p>
    </footer>
  </div>
</template>


<style scoped>
.pagina {
  background-color: #f2f4f7;
}

.presentacion {
  background-color: #4b3f72;
  text-align: center;
  padding: 30px;
}

.title {
  margin: 10px;
}

.highlight {
  color: yellow;
}

.white {
  color: white;
}

.contenido {
  width: 90%;
  max-width: 1000px;
  margin: 30px auto;
}

.informacion {
  background-color: white;
  padding: 25px;
  margin-bottom: 20px;
  border-radius: 10px;
  color: #000000;
}

.informacion h2 {
  color: #4b3f72;
}

.materias {
  background-color: #e8f5e9;
  padding: 25px;
  border-radius: 10px;
  margin-bottom: 20px;
  color: #000000;
}

.materias h2 {
  color: #2e7d32;
}

.habilidades {
  background-color: #efe0ff;
  padding: 25px;
  border-radius: 10px;  
  color: #000000;
}

.habilidades h2 {
  color: #030104;
}

.pie {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 25px;
}

.pie h3 {
  color: #ffd54f;
}

</style>
