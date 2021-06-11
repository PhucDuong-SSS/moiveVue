<template>
  <div class="container mx-auto " >
    <div class="flex justify-between  border-b border-gray-500">
       <Navbar/>
    <Searchbar/>
    </div>   
    <PopularMovies/>
  </div>
</template>

<script>
import Navbar from './header/Navbar.vue'
import Searchbar from './header/Searchbar.vue'
import PopularMovies from './PopularMovie.vue'
export default {
name: 'home',
components: {
  Navbar,
  Searchbar,
  PopularMovies
}
}
</script>

<style>

</style>