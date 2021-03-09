<template>
  <div id="app">
    <Header />
    <Statistics />
    <WhatWeDo />
    <Slider />
    <Team />
    <About />
    <Contact class="contact"/>
    <Form />
    <Footer />
  </div>
</template>

<script>
import Header from './components/header/Header.vue'
import Statistics from './components/body/Statistics.vue'
import WhatWeDo from './components/body/WhatWeDo.vue'
import Slider from './components/body/Slider.vue'
import Team from './components/body/Team.vue'
import About from './components/body/About.vue'
import Contact from './components/body/Contact.vue'
import Form from './components/body/Form.vue'
import Footer from './components/footer/Footer.vue'
export default {
  name: 'App',
  components: {
    Header,
    Statistics,
    WhatWeDo,
    Slider,
    Team,
    About,
    Contact,
    Form,
    Footer
  }
}
</script>

<style>
#app {
  margin-top: 20px;
}
.contact{
  margin-top: -230px;
}
</style>
