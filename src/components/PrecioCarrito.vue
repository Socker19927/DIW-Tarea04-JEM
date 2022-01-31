<template>
  <div id="precio">
    <section id="producto-datos">
        <h1>Edición Coleccionista </h1>
        <h1>World of Warcraft Shadowlands</h1>
        <h2>119,99€ <span class="iva">sin IVA: 94.79€</span></h2>
        <div class="wrapper">
            <button class="btn" @click="cambiarContador('-1')" type="button" name="button">-</button>
            <input class="cantidad" type="text" name="name" :value="contador">
            <button class="btn" @click="cambiarContador('1')" type="button" name="button">+</button>
        </div>
        <br>
        <button class="boton"><span class="fa fa-shopping-cart"></span> AÑADIR CARRITO</button>
    </section>
  </div>
</template>

<script>
export default {
  Name: 'ProductoDatos',
    data () {
        return {
            contador: 1
        }
    },
    methods: {
        cambiarContador(num) {
            this.contador += +num;
            if (!isNaN(this.contador) && (this.contador < 0)) {
              this.contador = 0
            }
        }
    }


}
</script>

<style scoped>
section#producto-datos {
  flex: 1 1 18rem;
  align-content: center;
  align-items: center;
  justify-content: center;
}
h1 {
  font-size: 2.2rem;
  color: #2c0e05;
}
h2 {
  font-size:1.7rem;
  color: #da5e0c;
}
span.iva {
  font-size:1rem;
  font-weight: normal;
  color: #282828
}
.wrapper {
  height: 2rem;
  display: flex;
  justify-content: center;
}

.cantidad {
  border: none;
  text-align: center;
  width: 2rem;
  font-size: 1.2rem;
  border: 1px solid #d8d8d8;
}
.btn {
  border: 1px solid #d8d8d8;
  width: 1.8rem;
}
button:focus, input:focus {
  outline: 0;
}
#precio{
  align-content: center;
  align-items: center;
  justify-content: center;
}
.boton{
  background-color: #53d669;
  padding: 0.5rem;
}
</style>