<template>
  <div id="app" class="vh-100">
    <!-- bg-green-600 py-56 min-h-screen -->
    <div class="container text-center px-8">
      <!--  mx-auto  -->
      <div class="vh-100">
        <img src="./assets/v2.png">
      </div>
      <h2 class="text-3xl lg:text-6xl font-bold mb-2 text-white">Welcome to Your Vue App</h2>
      <h3 class="text-xl lg:text-4xl text-green-200">
        Deployed to
        <span
          class="font-bold bg-clip-text text-transparent bg-gradient-to-br from-blue-400 via-purple-400 to-blue-500"
        >DigitalOcean</span>
      </h3>

      <div class="flex justify-center space-x-2 mt-6 lg:mt-10">
        <a
          href="https://www.digitalocean.com/docs/app-platform"
          class="inline-block py-2 lg:py-4 px-4 lg:px-8 rounded bg-green-500 hover:bg-green-400 text-green-100 shadow hover:shadow-2xl transition duration-300"
        >View the Docs</a>
        <a
          href="https://cloud.digitalocean.com/apps"
          class="inline-block py-2 lg:py-4 px-4 lg:px-8 rounded bg-yellow-400 hover:bg-yellow-300 text-yellow-800 shadow hover:shadow-2xl transition duration-300"
        >View Your Dashboard</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  };
</script>

<style>
#app {
  background-color: #000000;
}
.fit img {
    object-fit: contain;
}
</style>