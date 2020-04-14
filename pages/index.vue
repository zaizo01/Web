<template>
  <div class>
    <div
      class="bg-cover bg-center h-auto py-64 w-screen h-screen"
      style="background-image: url(https://images.unsplash.com/photo-1534361960057-19889db9621e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80)">
      <nav class="text-white ml-6 -mt-56">
        <a href class="mr-6 font-semibold">Home</a>
        <nuxt-link to="/gallery"><a href class="mr-6">Gallery</a> </nuxt-link>
        <nuxt-link to="/adopt"><a href class="mr-6">Adopt</a> </nuxt-link>
      </nav>
      <div class="text-white md:w-1/2 ml-6 mt-40">
        <p class="text-6xl font-bold">Dog App</p>
        <p
          class="font-medium"
        >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Explicabo debitis architecto recusandae voluptatem. Possimus, eius nisi, eos ipsum iure eaque sunt libero exercitationem earum illum, labore ratione nesciunt illo ipsa.</p>
        <button class="bg-blue-500 text-white font-bold py-2 px-10 rounded-full mt-4">Get Started</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
</style>
