<template>
  <div>
    <h1 class="text-white">Movies Section</h1>
    <Carousel :perPage="5" :paginationEnabled="false" :navigationEnabled="true" :loop="true">
      <Slide v-for="movie in movies" :key="movie.id">
        <div class="px-1">
          <router-link :to="'/watch/' + movie.id">
            <b-img :src="movie.banner" rounded height="200" />
          </router-link>
        </div>
      </Slide>
    </Carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel';

export default {
  components: {
    Carousel,
    Slide,
  },
  props: {
    movies: {
      type: Array,
    },
  },
};
</script>

<style>
.VueCarousel-navigation-button {
  color: white !important;
  align-content: center;
  margin: 1%;
}
</style>
