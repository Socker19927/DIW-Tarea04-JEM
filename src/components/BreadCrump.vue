<template>
  <section id="camino-migas">
      <a class="inicio" href="#"> Inicio </a> <span>/</span>
      <a href="#">PC </a><span>/</span>
      <a class="actual" href="#">World of Warcraft</a> 


  </section>
</template>

<script>
export default {

}
</script>

<style>
section#camino-migas {
    margin-left: 1rem;
    display:flex;
    margin-top: 1rem;
}
section#camino-migas a, 
section#camino-migas a:hover, 
section#camino-migas a:visited{
    text-decoration: none;
    font-size: 1.2rem;
    margin-left: 1rem;
    margin-right: 1rem;
    color: #a1490d;
}
section#camino-migas a.actual {
    font-weight: 700;
}
section#camino-migas {
    margin-left: 1rem;
    color: #1abc9c;
}

span{
    color: #da5e0c;
    font-weight: 900;
}
</style>