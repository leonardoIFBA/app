<script setup >
  const mensagem = "Ola Mundo!!"
  const nome = "MAriada asasa"
  const n1 = 10
  const n2 = 20
</script>

<template>
  <!-- testando interpolar -->
  <h1> {{ mensagem }} </h1>

  <h1> {{mensagem + " Seja bem vindo " + nome}} </h1>

  <p> {{ n1 + n2}} </p>
</template>

<style scoped></style>