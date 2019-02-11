<template>
  <div class="hello">
  <nav>
    <ul class="navbar">
      <li><a href="">Accueil</a></li>
      <li><a href="">Produit</a></li>
      <li><a href="">solde</a></li>
      <li><a href="">Nous contacter</a></li>
    </ul>
  </nav>
    <h1>EPEC FINAL PROJET</h1>

    <div id="input">
      <label>Ajouter un produit : </label>
      <input type="text" placeholder="ajouter produit ...">
    </div>
    <div class="listproduits">
      <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
    </div>
    

   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data: {

  },
  methods: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  width: 90%;
  margin: auto;
}
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
.navbar {
  
  display: flex;
  justify-content: flex-start;
  align-items: center;
  margin: auto;
  background: hsl(202, 81%, 64%);
  width: 100%;
  height: 60px;
}
ul li a {
  color: white;
  text-decoration: none;
}

</style>
