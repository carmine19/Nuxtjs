<template>
  <div class="container">
    <div>
      <!-- importo il logo come componente dalla cartella components -->
      <Logo />
      <h1 class="title">
        about
      </h1>
      <!-- possiamo passare i parametri nelle rotte crendo un file con l'underscore o crando la cartella con
       l'underscore e passare il parametro nella index, per vedere poi se funziona passiamo alla funzione
       $route-->
      <h2>parametro {{$route.params.id}}</h2>
    </div>
  </div>
</template>

<script>
export default {}


</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
