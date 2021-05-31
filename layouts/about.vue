<!-- possiamo creare diversi layout per le nostre pagine che poi importiamo nei componenti o pagine di cui
  ne abbiamo bisogno, in questo caso ho creato un componete di layouts about che ho importato in about.index,
  per far leggere il componente bisogna richiamarlo in js con layout : 'nomecomponente'-->
<template>
  <div>
    <!-- qui importo globalmente i componeti che uso -->
    <h1>about layouts</h1>
    <Nav />
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}


a {
  color: red;
  text-decoration: none;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}


</style>
