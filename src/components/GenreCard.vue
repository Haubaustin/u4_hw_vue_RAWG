<template>
  <div class="card">
    <div class="image-wrapper">
      <img :src="genre.image_background" />
    </div>
    <div class="info-wrapper flex-col">
      <h3>{{genre.name}}</h3>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'GenreCard',
    props: {
      genre: {}
    }
  }
</script>
