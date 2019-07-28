<template>
  <div id="app">
    <Header />
    <div role="main" class="main">
      <Slider />
      <Intro />
<<<<<<< HEAD
<<<<<<< HEAD
=======
      <Testimonials />
>>>>>>> 0970541d850e9df4994f5869b61d562098e81e7e
=======
      <Testimonials />
>>>>>>> dev
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Slider from './components/Slider.vue'
import Intro from './components/Intro.vue'
import GetStarted from './components/GetStarted.vue'
<<<<<<< HEAD
<<<<<<< HEAD
=======
import Testimonials from './components/Testimonials.vue'
>>>>>>> 0970541d850e9df4994f5869b61d562098e81e7e
=======
import Testimonials from './components/Testimonials.vue'
>>>>>>> dev

export default {
  name: 'app',
  metaInfo: {
    title: "You Genius",
    script:[
<<<<<<< HEAD
<<<<<<< HEAD
      {src: 'master/style-switcher/style.switcher.localstorage.js'},
      {src: 'vendor/modernizr/modernizr.min.js'},
=======
>>>>>>> dev
      {src: 'vendor/jquery/jquery.min.js', async: true},
      {src: 'js/demos/demo-education.js', defer: true, body: true},
<<<<<<< HEAD
      {src: 'js/theme.init.js', defer: true, body: true}
=======
      {src: 'vendor/jquery/jquery.min.js', async: true},
      {src: 'js/demos/demo-education.js', defer: true, body: true},
      {src: 'js/theme.init.js', body: true}
>>>>>>> 0970541d850e9df4994f5869b61d562098e81e7e
=======
      {src: 'js/theme.init.js', body: true}
>>>>>>> dev
    ]
 },
  components: {
    Footer,
    Header,
    Slider,
    Intro,
<<<<<<< HEAD
<<<<<<< HEAD
    GetStarted
=======
    GetStarted,
    Testimonials
>>>>>>> 0970541d850e9df4994f5869b61d562098e81e7e
=======
    GetStarted,
    Testimonials
>>>>>>> dev
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
.appear-animation{
  opacity: 1;
}
</style>