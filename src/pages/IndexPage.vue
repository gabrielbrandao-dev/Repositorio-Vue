<template>

  <div>

    <q-row>
      <h2>{{frases.titulo}}</h2>
    </q-row>

    <q-row>
      <h5>{{frases.frase}}</h5>
    </q-row>

    <q-page class="flex flex-center">
        <img
        alt="Quasar logo"
        src="~assets/quasar-logo-vertical.svg"
        style="width: 300px; height: 300px"
      >
    </q-page>
  </div>

</template>

<script>

  export default {
    data() {

      return{
        frases: {
          frase: "A frase do dia é... Seja bondoso com todos, pois, oque você planta, no futuro há de ser colhido! ",
          titulo: "Bela Frase"
        }
      }
    }
  }

</script>
