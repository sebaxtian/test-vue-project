<template>

  <footer class="mdl-mini-footer">
    <div class="mdl-mini-footer__left-section">
      <ul class="mdl-mini-footer__link-list">
        <li>Sebaxtian ~ <a class="aboutme" href="http://about.me/sebaxtian" target="_blank">about.me/sebaxtian</a> ~ 2018</li>
      </ul>
    </div>
    <div class="mdl-mini-footer__right-section">
      <ul class="mdl-mini-footer__link-list">
        <li><a href="#">Ayuda</a></li>
        <li><a href="#">Terminos & Privacidad</a></li>
      </ul>
    </div>
  </footer>

</template>

<script>
  export default {
    name: 'footer-component',
    data () {
      return {
        msg: 'Footer Component App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  footer {
    background-size: cover;
  }
</style>
