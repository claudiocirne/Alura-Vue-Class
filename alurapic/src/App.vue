<template>
  <div>
    <h1>{{ titulo }}</h1>

    <ul>
      <li v-for="foto de fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>
    
  </div>
</template>

<script>
export default {
  
    data() {

      return {
        titulo:'Alurapic',
        foto: []
      }
    },

    created() {

        alert('Criei o componente');
    }
}
</script>

<style>

</style>
