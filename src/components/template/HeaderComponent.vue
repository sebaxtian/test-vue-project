<template>

  <div class="mdl-layout__header-row portfolio-logo-row">
    <span class="mdl-layout__title">
      <div class="portfolio-logo"></div>
    </span>
  </div>

</template>

<script>
  export default {
    name: 'header-component',
    data () {
      return {
        msg: 'Header Component App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .mdl-layout__title {
    font-size: 14px;
    text-align: center;
    font-weight: 300;
  }
  .portfolio-logo-row {
    min-height: 200px;
  }
  .portfolio-logo {
    background: url(../../assets/images/logo.png) 50% no-repeat;
    background-size: contain;
    height: 200px;
    width: 200px;
    background-position: center;
    margin: auto auto 10px;
  }
  .is-compact .mdl-layout__title span {
    display: none;
  }
  .is-compact .portfolio-logo-row {
    min-height: auto;
  }
  .is-compact .portfolio-logo {
    background-position: center;
    background-size: 90%;
    height: 60px;
    width: 60px;
    margin-top: 7px;
  }
</style>
