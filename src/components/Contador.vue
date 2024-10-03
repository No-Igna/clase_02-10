<script>
  export default{
    name: "Contador",
    data(){
      return{
        contador: 0,

      }
    }
  }
</script>
<template>
  <div>
    <h1>el valor actual de contador es: {{ contador }}</h1>
    <button @click="contador++">incrementar</button>
  </div>
</template>
<style>
</style>