<template>
  <div>
    <h2 class="mt-5 text-yellow-500 uppercase font-semibold">Populer Movies</h2>
    <MovieItem/>
  </div>
</template>

<script>
import MovieItem from './items/MovieItem.vue'
export default {
components : {
  MovieItem
}
}
</script>

<style>

</style>