<script setup>
import imagen from "../assets/img/grafico.jpg";
</script>
<template>
  <div class="dos-columnas">
    <div class="contenedor-grafico">
      <img :src="imagen" alt="Imagen del grafico" />
    </div>

    <div class="contenedor-presupuesto">
      <button class="reset-app">Resetear App</button>
      <p>
        <span>Presupuesto:</span>
        0
      </p>
      <p>
        <span>Disponible:</span>
        0
      </p>
      <p>
        <span>Gastado:</span>
        0
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
