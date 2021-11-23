<!-- Create e utilizzate un componente Title, il quale contiene un titolo che recita “La mia prima app con Vue CLI!” -->

<template>
  <h1>La mia prima app con Vue CLI</h1>
</template>

<script>
export default {
  name: 'myTitle'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  margin: 40px 0;
  font-weight: 900;
  color: #010008;
  text-shadow: 20px 20px 5px #d3d3d3;
}
</style>