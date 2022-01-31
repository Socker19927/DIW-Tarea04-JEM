<template>
  <section id="cabecera">
      <div class="container">
        <img src="../assets/logo.png" alt="Logo de la empresa" copyright="Jose Egea Monserrate">
      </div>
      <section id="barra-busqueda">
        <form @submit.prevent="handleEnviar">
            <input type="text" placeholder="MInecraft, rpg, multiplayer...">
            <button class="boton1">Buscar</button>
        </form>
      </section>
      <div id="carrito">
            
            <button class="boton1" style="font-size:24px"> <i class="fa fa-shopping-cart"></i></button>
      </div>
  </section>
  
</template>

<script>
export default {
    name: 'BarraBusqueda',
    methods: {
        handleSutmit() {
            console.log("Busqueda enviada")
        }
    }
}
</script>

<style>

#cabecera{
    display: flex;
    text-align: left;
    background-color: black;
    align-content: space-between;
}

section#cabecera img {
    margin: 1rem;
    height: 5rem;
}
section#barra-busqueda {
    margin: 1rem;
    display: flex;
    flex-grow: 1;
    align-content: center;
}
section#barra-busqueda form {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-grow: 1;
}
section#barra-busqueda input{
    margin: 1rem;
    padding: 0.5rem 1rem;
    border-style: solid;
    border: 2px solid #da5e0c;
    color: #181818;
    outline: none;
    line-height: 1.4rem;
    border-radius: 25px;
    font-size: 1.2rem;
    background-color: #721c24;
}
#carrito{
    width: 15rem;
    align-content: center;
    align-items: center;
    justify-content: center;
    margin-top: 2rem;
   
}

.boton1{
    background-color: #721c24;
    display: block;
    width: 54px;
    height: 50px;
    border-radius: 50%;
    color: white;
    font-weight: 500;
}

.boton1:hover{
    background-color: #da5e0c;
    display: block;
    width: 54px;
    height: 50px;
    border-radius: 50%;
    color: white;
    font-weight: 500;
}
</style>