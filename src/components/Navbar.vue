<template>
<nav>
  <ul class="navbar">
    <li>
      <a href="#">Recettes</a>
    </li>
    <li>
      <a href="#">Planning</a>
    </li>
    <li>
      <a href="#">Ajouter une recette</a>
    </li>
  </ul>
</nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
