<!-- Bonus:
Creare un secondo componente Hero, che visualizza un jumbotron.
 -->

<template>
  <section class="jumbotron">
      <h2>Sciacca</h2>
  </section>
</template>

<script>
export default {
  name: 'jumbotron'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 500px;
    width: 100%;
    background-image: url('../assets/sciacca.jpg');
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    background-color: #f3f2fd;
}

h2 {
    font-weight: 900;
    font-size: 50px;
    color: white;
    text-shadow: 0 0 10px black;
}
</style>