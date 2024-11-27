<template>
  <div class="hello">
    <h1 >{{ msg }}</h1>
    <p>
      Esta aplicación te permite gestionar tus tareas de manera eficiente. Puedes añadir nuevas <br> 
      tareas manualmente o extraerlas desde una API.    
    </p>
    <h3>SECCIONES</h3><br>
    <ul>
      <li><strong>AÑADIR TAREAS:</strong> Permite ingresar nuevas tareas manualmente.</li><br><br>
      <li><strong>LISTAR TAREAS:</strong> Muestra todas las tareas extraídas desde la API, permitiendo marcarlas como completadas o eliminarlas.</li><br><br>
      <li><strong>VISTA COMBINADA:</strong>Combina las funcionalidades de añadir tareas manualmente y ver las tareas de la API al mismo tiempo.</li>      
    </ul>   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
  font-weight: bold;
  color: rgb(142, 8, 163);
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
h1 {
  color: rgb(66, 6, 87);
  font-weight: bold;
}
</style>
