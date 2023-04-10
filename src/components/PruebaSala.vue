<template>
    <h2>Listados...</h2>
    <ul>
        <li>Nombre: {{this.empleado.name}}</li>
        <li>Edad: {{this.empleado.age}}</li>
        <li>Cargo: {{this.empleado.designation}}</li>
    </ul>
</template>

<script>
export default {
  name: "PruebaSala",
  data: function() {
    return {
      empleado: {
        name: "Sala",
        age: 25,
        designation: "Software Engineer"
      }
    };
  } 
};
</script>

<style>
</style>