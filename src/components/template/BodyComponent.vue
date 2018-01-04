<template>

  <main class="mdl-layout__content">
    <router-view/>
  </main>

</template>

<script>
  export default {
    name: 'body-component',
    data () {
      return {
        msg: 'Body Component App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
