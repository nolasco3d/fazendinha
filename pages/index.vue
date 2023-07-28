<template>
  <div class="container mx-auto h-screen">
    <div class="border border-gray:50 flex flex-col gap-4 items-center justify-center h-full">
      <h1 class="">Hello World!</h1>

      <router-link class="btn btn-primary w-64 rounded-full" to="/about">
        About page
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped>

</style>