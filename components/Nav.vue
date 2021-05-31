<!-- qui ho creato un componente che è la nav che importo globalmente in layouts -->
<template>
  <div class="">
    <nav>
      <ul>
        <li>
          <!-- usando nuxtlink il renderinf delle pagine è client side, volendo si può usare il link normarle
           per avere il rendering server side-->
          <NuxtLink to="about">about</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/">home</NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
