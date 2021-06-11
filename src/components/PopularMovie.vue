<template>
  <div class="mx-5">
    <h2 class="mt-5 text-yellow-500 uppercase font-semibold">Populer Movies</h2>
    <div class="grid grid-cols-1 sm:grid-cols-3 md:grid-cols-4 lg:cols-4 gap-8">
        <MovieItem/>
        <MovieItem/>
        <MovieItem/>
        <MovieItem/>
    </div>
    
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