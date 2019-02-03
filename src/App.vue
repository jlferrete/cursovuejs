<template>
  <div id="app">
    <barnav />
    <router-view/>
  </div>
</template>

<script>
  import Barnav from '@/components/Barnav'
  export default {
    name: 'app',
    components: {
      Barnav
    }
  }
</script>


<style>

</style>
