<template>
<section id="menu-principal">
    <div class="container">
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li> <img src="../assets/pcgaming.svg" alt="icono pc" copyright="Jose Egea Monserrate"><a href="#">PC</a></li>
            <li><img src="../assets/playstation.svg" alt="icono playstation" copyright="Jose Egea Monserrate"><a href="#">Playstation</a></li>
            <li><img src="../assets/xbox.svg" alt="icono xbox" copyright="Jose Egea Monserrate"><a href="#">Xbox</a></li>
            <li><img src="../assets/nintendo.svg" alt="icono nintendo" copyright="Jose Egea Monserrate"><a href="#">Nintendo</a></li>
        </ul>
    </nav>
    <div class=grupo>
        <a class="registro" href="#">REGISTRO</a>
        <a class="login" href="#">INICIAR SESIÓN</a>
    </div>
</div>
</section>
  
</template>

<script>
export default {

}
</script>

<style>
section#menu-principal {
    background: #2c0e05;
    z-index:999;
    padding:0.7rem;
}

section#menu-principal .container {
    display: flex;
    justify-content: center;
    align-items: center;
    align-content: center;
}

section#menu-principal .container nav ul {
    display:flex;
    list-style: none;
    padding: 0;
    margin:0rem 0.7rem;
}
section#menu-principal .container nav ul img{
   width: 1rem;
   align-items: center;
   align-content: center;
}
section#menu-principal .container nav ul li a{
  
    text-decoration: none;
    color:white;
    font-weight: 700;
    padding-left: 1rem;
    padding-right: 1rem;
    align-content: center;
}
section#menu-principal .container nav ul li ,.active, .registro, .login {

   
    text-decoration: none;
    color:white;
    font-weight: 700;
    padding: 1rem;
}

section#menu-principal .container nav a:hover{
    color: chocolate;
    font-weight: 1000;
}

.registro{
    color: #da5e0c;
}

.login{
    color: #d3844f;
}

.login:hover{
    color: #da5e0c;
    font-weight: 900;
}

.registro:hover{
    color: #d3844f;
    font-weight: 900;
}
</style>