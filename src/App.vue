<script setup>
const arrayCat = ["Petit y kids", "Juvenil", "Media", "Superior", "Posgrado"];
</script>


<template>
  <div class="block1">
    <h1 id="Titulo">Desarrollo de <br>aprendizaje en línea <br>para la enseñanza de <br>habilidades técnicas</h1>
    <button id="Boton1">nuestra convocatoria</button>
  <p id="Parrafo1">
    ¡Bienvenido a Concursed! La plataforma donde la creatividad y la <br>competencia se unen para brindarte la oportunidad de demostrar tus <br>habilidades y ganar grandes premios. Participa en nuestros concursos de <br>proyectos de creatividad, donde podrás presentar tus ideas y proyectos <br>para que sean evaluados por nuestros jueces expertos.</p>
  
    <div>
      
      <img src="./assets/camp1.png">
    </div>
  </div>

  <div class="block2">


  </div>

  <div class="block3">
    <h1 id="Titulo">Convocatoria</h1>
  <p id="Parrafo2">
    ¡Es hora de dejar volar tu imaginación! En nuestro próximo <br> concurso de proyectos de creatividad, buscamos ideas <br>innovadoras y originales en el tema de [tema del concurso]. Si <br>eres un creador, emprendedor o simplemente alguien<br> apasionado por la creatividad, ¡este es tu momento de brillar!</p>
    <h6>Categorias</h6>
    <ul>
    <li v-for="(categorias,index) in arrayCat" :key="index">
        {{ categorias }}
    </li>
  </ul>

  <button>Descarga la aquí!</button>

    <div>
      <img src="./assets/camp3.png">
    </div>
  </div>

  <div class="block4">


  </div>

  <div class="block5">


  </div>


  
  
  </template>

<style>
  #Titulo{
    font-family: 'Roboto', sans-serif;
  }

  #Parrafo1{
    font-family: 'Poppins', sans-serif;
  }

  .block1{
    width: 1950px;
    height: 750px;
    background-image: linear-gradient(to top, #fff1eb 0%, #ace0f9 100%);
  }

  .block3{
    width: 1950px;
    height: 750px;
    background-image: linear-gradient(to top, #ebbba7 0%, #cfc7f8 100%);
  }
</style>


