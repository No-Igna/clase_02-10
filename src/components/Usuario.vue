<script>
  export default{
    name: "usuario",
    data(){
      return{
        nombre: "John",
        apellido: "Doe",
        edad:"18"
      }
    }
  }
</script>
<template>
  <div>
    <p>el usuario es: {{ nombre }} {{ apellido }}, de {{ edad }} años.</p>
    <button @click="edad++">incrementar</button>
    <button @click="edad--">reducir</button>
    <p v-if="edad>=18">{{ nombre }} es mayor de edad</p>
    <p v-else>{{ nombre }} es menor de edad</p>
    <div>
      <label for="nuevoNombre">Cambiar nombre </label>
      <input type="text" id="nuevoNombre" v-model="nombre" placeholder="Ingresa un nombre">
    </div>
    <div>
      <label for="nuevoApellido">Cambiar Apellido </label>
      <input type="text" id="nuevoApellido" v-model="apellido" placeholder="Ingresa un Apellido">
    </div>
  </div>
</template>
<style>
</style>