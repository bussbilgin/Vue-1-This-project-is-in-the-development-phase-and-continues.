<template>
  <SearchBar />
  <Jumbotron />
  <Carousel />
  <BuyCards />
  <Partners />
</template>

<script>
import SearchBar from "../components/SearchBar.vue";
import Jumbotron from "../components/Jumbotron.vue";
import Carousel from "../components/Carousel.vue";
import BuyCards from "../components/BuyCards.vue";
import Partners from "../components/Partners.vue";

export default {
  name: "App",
  components: {
    SearchBar,
    Jumbotron,
    Carousel,
    BuyCards,
    Partners,
  },
};
</script>
