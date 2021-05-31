<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        Home
      </h1>
      <!-- con questo button attraverso la funzione goToUserId possiamo prendere andare a leggere e
       settare il paramentro id creato in abouts-->
      <div class="btn btn-danger" @click="goToUserId">User id: {{this.id}} </div>

    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      id : 6,
    }
  },

  methods: {

    goToUserId() {
      this.$router.push('/about/' + this.id)
    }
  }
}
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
