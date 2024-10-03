<script>
  export default{
    name: "saludo",
    data(){
      return{
        nombre:"Jose",
        apellido:"Perez",
        saludo:"Hola!"
      }
    }
  }
</script>
<template>
  <div>
    <h1>{{ saludo }}</h1>
    <p>{{ nombre }} {{ apellido }}</p>
  </div>
</template>
<style>
</style>