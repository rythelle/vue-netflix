<template>
  <div class="home">
    <MoviesSections :movies="movies" class="mt-5" />
    <MoviesSections :movies="movies" class="mt-5" />
    <MoviesSections :movies="movies" class="mt-5" />
  </div>
</template>

<script>
import MoviesSections from '../components/MoviesSections.vue';

export default {
  name: 'Home',
  components: {
    MoviesSections,
  },
  data() {
    return {
      movies: [
        {
          id: 1,
          banner:
            'https://conteudo.imguol.com.br/c/entretenimento/65/2021/12/14/cartaz-de-homem-aranha-sem-volta-para-casa-1639517284758_v2_450x337.jpg',
        },
        {
          id: 2,
          banner:
            'https://observatoriodocinema.uol.com.br/wp-content/uploads/2021/02/homem-de-ferro-tony-divulgacao.jpg',
        },
        {
          id: 3,
          banner: 'https://images.universohq.com/2016/01/SnoopyCharlieBrawnPeanuts02_des.jpg',
        },
        {
          id: 4,
          banner:
            'https://midias.correiobraziliense.com.br/_midias/png/2021/10/01/675x450/1_pasted_image_0__2_-6896675.png',
        },
        {
          id: 5,
          banner: 'https://t.ctcdn.com.br/31dtSbE11cqCv_f24HuPGRzE2-A=/512x288/smart/i887.jpeg',
        },
        {
          id: 6,
          banner:
            'https://studiosol-a.akamaihd.net/tb/letras-blog/wp-content/uploads/2021/06/5d43f01-shrek-1024x576.jpg',
        },
        {
          id: 7,
          banner:
            'https://conteudo.imguol.com.br/c/entretenimento/65/2021/12/14/cartaz-de-homem-aranha-sem-volta-para-casa-1639517284758_v2_450x337.jpg',
        },
        {
          id: 8,
          banner:
            'https://observatoriodocinema.uol.com.br/wp-content/uploads/2021/02/homem-de-ferro-tony-divulgacao.jpg',
        },
        {
          id: 9,
          banner: 'https://images.universohq.com/2016/01/SnoopyCharlieBrawnPeanuts02_des.jpg',
        },
        {
          id: 10,
          banner:
            'https://midias.correiobraziliense.com.br/_midias/png/2021/10/01/675x450/1_pasted_image_0__2_-6896675.png',
        },
        {
          id: 11,
          banner: 'https://t.ctcdn.com.br/31dtSbE11cqCv_f24HuPGRzE2-A=/512x288/smart/i887.jpeg',
        },
        {
          id: 12,
          banner:
            'https://studiosol-a.akamaihd.net/tb/letras-blog/wp-content/uploads/2021/06/5d43f01-shrek-1024x576.jpg',
        },
      ],
    };
  },
};
</script>
