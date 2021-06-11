<template>
  <div class="mt-5 flex relative">
    <input
      type="text"
      class=" rounded-full bg-gray-600 px-7 w-50 h-10 mr-3 focus:outline-none "
      placeholder="Search ..."
    />
    <div class="absolute top-0">
      <svg
        class="fill-current w-4 text-gray-300 mt-2 ml-2 mt-3"
        viewBox="0 0 24 24"
      >
        <path
          class="heroicon-ui"
          d="M16.32 14.9l5.39 5.4a1 1 0 01-1.42 1.4l-5.38-5.38a8 8 0 111.41-1.41zM10 16a6 6 0 100-12 6 6 0 000 12z"
        />
      </svg>
    </div>
    <div v-if="false" class="absolute mt-12 ml-2 rounded bg-gray-600 w-60">
      <ul>
        <li class="flex items-center border-b border-gray-300 p-1 ">
          <img src="@/assets/images/joker.jpg" class="w-10 " alt="" />
          <span class="ml-2">Die hard</span>
        </li>
      </ul>
    </div>
    <img src="@/assets/images/avatar.jpg" alt="" class="h-10 rounded-full" />
  </div>
</template>

<script>
    export default {};
</script>

<style></style>