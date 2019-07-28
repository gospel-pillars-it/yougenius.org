<template>
  <div id="app">
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  metaInfo: {
    title: "You Genius",
    script:[
      {src: 'master/style-switcher/style.switcher.localstorage.js'},
      {src: 'vendor/modernizr/modernizr.min.js'},
      {src: 'vendor/jquery/jquery.min.js'},
      {src: 'vendor/jquery.appear/jquery.appear.min.js', defer: true, body: true},
      {src: 'vendor/jquery.easing/jquery.easing.min.js', defer: true, body: true},
      {src: 'vendor/jquery.cookie/jquery.cookie.min.js', defer: true, body: true},
      {src: 'master/style-switcher/style.switcher.js', id: 'styleSwitcherScript', defer: true, body: true},
      {src: 'vendor/popper/umd/popper.min.js', defer: true, body: true}
    ]
  },
  components: {
    Footer
  }
}
</script>

<style>
@import url('vendor/bootstrap/css/bootstrap.min.css');
@import url('vendor/fontawesome-free/css/all.min.css');
@import url('vendor/animate/animate.min.css');
@import url('vendor/simple-line-icons/css/simple-line-icons.min.css');
@import url('vendor/owl.carousel/assets/owl.carousel.min.css');
@import url('vendor/owl.carousel/assets/owl.theme.default.min.css');
@import url('vendor/magnific-popup/magnific-popup.min.css');
@import url('css/theme.css');
@import url('css/theme-elements.css');
@import url('css/theme-blog.css');
@import url('css/theme-shop.css');
@import url('vendor/rs-plugin/css/settings.css');
@import url('vendor/rs-plugin/css/layers.css');
@import url('vendor/rs-plugin/css/navigation.css');
@import url('vendor/rs-plugin/css/layers.css');
@import url('css/demos/demo-education.css');
@import url('css/skins/skin-education.css');
@import url('css/custom.css');
</style>