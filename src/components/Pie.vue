<template>
<footer>
   
    <div class="flex_row">
      <div id="logo"><img id="footerLogo" src="../assets/logo.png " alt="Logo Pie" copyright="Jose Egea Monserrate"></div>
      <div class="flex_grow">
        <span id="copy">© Copyright 2021 - Todos los derechos reservados</span>
        </div>
     
      <div>
        <div class="flex_col">
          <div>
          
          </div>
          <div id="iconFooter">
            <a id="contacto" href="#">¡Contacta!</a>
            <a id="conocenos" href="#">¿Quienes somos?</a>
            <a id="facebook"  href=""><img class="iconFooter" src="../assets/fb.png" alt="icono facebook" copyright="Jose Egea Monserrate"></a>
            <a id="twitter"  href=""><img class="iconFooter" src="../assets/tw.png" alt="icono twitter" copyright="Jose Egea Monserrate"></a>
            <a id="instagram"  href=""><img class="iconFooter" src="../assets/inst.png" alt="icono instagram" copyright="Jose Egea Monserrate"></a>
            <a id="youtube"  href=""><img class="iconFooter" src="../assets/yt.png" alt="icono youtube" copyright="Jose Egea Monserrate"></a>
          </div>
        </div>
      </div>
    </div>
 

  </footer>
</template>

<script>
export default {

}
</script>

<style>

/*Pie de pagina*/

footer
{
    width: 100%;
    height: 200px;
    background-color:#000000;
    margin-top: 1%;
}

footer div
{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-left: 1%;
    padding-right: 1%;
}

#footerLogo
{
    width: 50%;
    height: 50%;
    padding-top: 8%;
}
#logo{
  display: flex;
  align-items: center;
  align-content: center;
}

footer .iconFooter
{
    width: 60px;
    height: 60px;
}

#iconFooter
{
    padding-top: 20%;
}
.flex_row
{
    display: flex;
    flex-direction: row;
}

.flex_col
{
    display: flex;
    flex-direction: column;
}

.flex_grow
{
    display: flex;
    flex-grow: 1;
}

#copy{
  color: white;
  margin-top: 20%;
}

#conocenos{
  color: white;
  text-decoration: none;
}

#contacto{
  color: white;
  text-decoration: none;
}
</style>