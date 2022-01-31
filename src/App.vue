<template>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <Cabecera/>
  <Principal/>
  <BreadCrump/>
  <div class="dos-seciones">
    <ImagenesJuegos/>
    <PrecioCarrito/>
  </div>
    <DescripcionVideo/>
  <Pie/>

</template>

<script>
import Cabecera from './components/Cabecera'
import Principal from './components/Principal.vue'
import BreadCrump from './components/BreadCrump'
import ImagenesJuegos from './components/ImagenesJuegos'
import PrecioCarrito from './components/PrecioCarrito'
import DescripcionVideo from './components/DescripcionVideo'
import Pie from './components/Pie'



export default {
  name: 'App',
  components: {
    Cabecera,Principal,BreadCrump,ImagenesJuegos,PrecioCarrito,DescripcionVideo,Pie
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&family=Titillium+Web:wght@300;400;700&display=swap');
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 5px;
  margin-right: 15px;
  margin-left: 15px;
  background-color: #d0dae0;
}

.dos-seciones{
  display: flex;
  margin: 1rem;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: row;
}
.container {
    max-width: 1400px;
    margin: auto;
}

</style>
