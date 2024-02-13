<template>
  <div id="container">
    <h1>
      Virgin Vue
    </h1>

    <p class="message">{{ message }}</p>
    <button @click="changeMessage">Cambiar Mensaje</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Este es un mensaje dentro del componente."
    };
  },
  methods: {
    changeMessage() {
      this.message = "Nuevo mensaje cambiado por el botón.";
    }
  }
}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

*{
  font-family: 'Roboto', sans-serif;
}

#container{
  text-align: center;
}

#container .message {
  color: red;
}

@media only screen and (max-width: 480px) {
  /* Tus estilos específicos para dispositivos móviles aquí */
  #container {
    widows: 400px;
    margin: 0 auto;
  }
}

</style>
