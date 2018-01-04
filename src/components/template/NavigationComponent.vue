<template>

  <nav class="mdl-navigation mdl-typography--body-1-force-preferred-font">
    <a class="mdl-navigation__link" href="#">Page 1</a>
    <a class="mdl-navigation__link" href="#">Page 2</a>
    <a class="mdl-navigation__link" href="#" target="_blank">Page 3</a>
    <a class="mdl-navigation__link" href="#">Page 4</a>
    <a class="mdl-navigation__link" href="#">Page 5</a>
    <a class="mdl-navigation__link" href="#">Page 6</a>
    <a class="mdl-navigation__link" href="#">Page 7</a>
    <a class="mdl-navigation__link" href="#">Page 8</a>
  </nav>

</template>

<script>
  export default {
    name: 'navigation-component',
    data () {
      return {
        msg: 'Navigation Component App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .mdl-navigation {
    max-width: 900px;
    width: 100%;
  }
  .mdl-navigation__link {
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    line-height: 42px;
  }
</style>
