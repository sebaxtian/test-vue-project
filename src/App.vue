<template>

  <div id="app">

    <div class="mdl-layout mdl-js-layout mdl-layout--fixed-header">

      <header class="mdl-layout__header mdl-layout__header--waterfall portfolio-header">
        <header-component/>
        <div class="mdl-layout__header-row portfolio-navigation-row mdl-layout--large-screen-only">
          <navigation-component/>
        </div>
      </header>

      <div class="mdl-layout__drawer mdl-layout--small-screen-only">
        <navigation-component/>
      </div>

      <body-component/>

      <footer-component/>

    </div>

  </div>

</template>

<script>
  import HeaderComponent from './components/template/HeaderComponent'
  import NavigationComponent from './components/template/NavigationComponent'
  import BodyComponent from './components/template/BodyComponent'
  import FooterComponent from './components/template/FooterComponent'

  export default {
    name: 'app',
    components: {
      HeaderComponent,
      NavigationComponent,
      BodyComponent,
      FooterComponent
    }
  }
</script>

<style>
  .portfolio-header {
    position: relative;
    background-color: #424242;
  }
  .portfolio-header .mdl-layout__header-row {
    padding: 0;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }
  .portfolio-navigation-row {
    background-color: rgba(0, 0, 0, 0.08);
    text-transform: uppercase;
    height: 45px;
  }
</style>
