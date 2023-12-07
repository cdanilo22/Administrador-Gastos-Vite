<script setup>
  import Presupuesto from './components/Presupuesto.vue';
</script>

<template>
<div>
  <header>
    <h1>Planificador de Gastos</h1>

    <div class="contenedor-header contenedor sombra"></div>

    <Presupuesto
    />

  </header>
  <Filtro/>

</div>



</template>

<style>
:root{
  --azul: #3b82f6;
  --blanco: #FFF;
  --gris--claro: #F5F5F5;
  --gris: #94a3b8;
  --gris-oscuro: #64748b;
  --negro: #000;
}

html{
  font-size: 62.5%;
  box-sizing: border-box;
}

*,
*:before,
*:after{
  box-sizing: inherit;
}
body{
  font-size: 1.6rem;
  font-family: "Lato", sans-serif;
  background-color: var(--gris--claro);
}

h1{
  font-size: 4rem; /** equivalente a 40px */
}

h2{
  font-size: 3rem;
}
header{
  background-color: var(--azul);
}
header h1{
  padding: 3rem 0;
  margin: 0;
  color: var(--blanco);
  text-align: center;

}

.contenedor{
  width: 90%;
  max-width: 80%;
  margin: 0 auto;
}

.contenedor-header{

}

.sombra{

}


</style>
