<template>
  <div id="homepage">
    <Header />
    
    <main>
      <About />
      <ParallaxSection />
      <MenuPricing />
      <DrinksPricing />
      <Reservation />
    </main>

    <Footer />
  </div>
</template>

<script>
import Header from '../components/Homepage/Header.vue';
import About from '../components/Homepage/About.vue';
import DrinksPricing from '../components/Homepage/DrinksPricing.vue';
import MenuPricing from '../components/Homepage/MenuPricing.vue';
import ParallaxSection from '../components/Homepage/ParallaxSection.vue';
import Reservation from '../components/Homepage/Reservation.vue';


export default {
  components: {
    Header,
    About,
    DrinksPricing,
    MenuPricing,
    ParallaxSection,
    Reservation
  }
}
</script>

<style>
.container-fluid{
  width: 90%;
  margin: 0 auto;
}
.container{
  width: 80%;
  margin: 0 auto;
}
a{
  text-decoration: none;
}
.btn-book-now{
  padding: 10px 15px;
  border: 2px solid #fff;
}
</style>
