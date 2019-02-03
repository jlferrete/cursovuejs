<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Galeria></Galeria>

  </div>
</template>

<script>
// @ is an alias to /src
import Galeria from '@/components/Galeria.vue'

export default {
  name: 'home',
  components: {
    Galeria
  }
}
</script>
