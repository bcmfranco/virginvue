<template>
    <div class="container">
      <h2>Player Name</h2>
      <div class="jugador">
        <div class="cabeza"></div>
        <div class="camiseta"></div>
        <div class="short"></div>
        <div class="piernas">
            <div class="piernaizq"></div>
            <div class="piernader"></div>
        </div>
        <div class="medias">
            <div class="mediaizq"></div>
            <div class="mediader"></div>
        </div>

      </div>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
    :host {
      --piel: white;
      --pelo: white;
      --camiseta: white;
      --pantalon: white;
      --pierna: white;
      --botas: white;
      --borde: black;
    }
  
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  
    h2 {
      color: black;
      margin-bottom: 10px;
    }
  
    .jugador {
        display: block;
    }

    .cabeza{
        border: 1px solid black;
        width: 100px;
        height: 100px;
        display: block;
        margin-left: 50px;
    }

    .camiseta{
        border: 1px solid black;
        width: 200px;
        height: 100px;
    }

    .short{
        border: 1px solid black;
        width: 200px;
        height: 50px;
    }

    .piernas{
        display: flex;
        flex-direction: row;
    }

    .piernaizq,
    .piernader{
        border: 1px solid black;
        width: 100px;
        height: 25px;
    }

    .medias{
        display: flex;
        flex-direction: row;
    }

    .mediaizq,
    .mediader{
        border: 1px solid black;
        width: 100px;
        height: 25px;
    }


  

  </style>
  