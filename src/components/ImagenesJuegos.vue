<template>
<section id="producto">
    <section id="producto-imagen">
      <div class="img-big"> 
          <img v-bind:src="fotos[0]" alt="Portátil Huawei MateBoot X">
      </div>
        <div class="img-mini">
          <a @click="cambiarFoto(1)"><img  v-bind:src="fotos[1]" alt="Juego World of warcraft Shadowlands" copyright="Jose Egea Monserrate"></a>
          <a @click="cambiarFoto(2)"><img  v-bind:src="fotos[2]" alt="Juego World of warcraft Shadowlands" copyright="Jose Egea Monserrate"></a>
          <a @click="cambiarFoto(3)"><img  v-bind:src="fotos[3]" alt="Juego World of warcraft Shadowlands" copyright="Jose Egea Monserrate"></a>
          <a @click="cambiarFoto(4)"><img  v-bind:src="fotos[4]" alt="Juego World of warcraft Shadowlands" copyright="Jose Egea Monserrate"></a>
        </div>
    </section> 
</section>
</template>

<script>
export default {
    Name: 'ProductoImagen',
    data () {
        return {
            fotos: [
                require ('../assets/e1.png'),
                require ('../assets/e1.png'),
                require ('../assets/e2.png'),
                require ('../assets/e3.png'),
                require ('../assets/e4.png')]
        }
    },
    methods: {
        cambiarFoto(id) {
            this.fotos[0] = this.fotos[id]
        }
    }

}


</script>

<style escoped>
#producto{
    display: flex;
    flex-direction: row;
}
#producto-imagen {
    border-radius: 25px;
    padding: 1rem;
    margin: 1rem;
    flex: 0 1 50%;
}
.img-mini {
    display: flex;
    justify-content: center;
    align-items: flex-start;
}
.img-mini img {
    width: 100px;
    border:2px solid #d8d8d8;
    margin-right: 2rem;
   
}
.img-big img{
    max-width: 50rem;
}
</style>