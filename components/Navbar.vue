<template>
  <div class="flex justify-end border py-1.5">
    <button><img src="/github.png" alt="github" class="absolute  left-10 top-2 w-14" v-on:click="clickToGit"></button>
    <button v-on:click="clickToGit" class="absolute mr-10 left-16 py-4 px-8 blue-500 text-green-400 text-xl font-semibold"> Github.com</button>
    <button v-on:click="clickToGoogle" class="mr-6 py-4 px-8 blue-500 text-green-400 text-xl font-semibold">Google</button>
    <button v-on:click="clickToYt" class="mr-6 py-4 px-8 blue-500 text-green-400 text-xl font-semibold">Youtube</button>
    <button v-on:click="clickToTw" class="mr-6 py-4 px-8 blue-500 text-green-400 text-xl font-semibold">Twitter</button>
    <button v-on:click="clickToFb" class="mr-6 py-4 px-8 blue-500 text-green-400 text-xl font-semibold">Facebook</button>
    <button v-on:click="clickToAbout" class="mr-6 py-4 px-8 blue-500 text-green-400 text-xl font-semibold">About Me</button>
  </div>
</template>

<script>
export default {
  methods: {
    clickToGit(){
      window.location = "https://github.com/wayuee/"
    },
    clickToGoogle(){
      window.location = "https://google.com"
    },
    clickToYt(){
      window.location = "https://youtube.com"
    },
    clickToTy(){
      window.location = "https://twitter.com"
    },
    clickToFb(){
      window.location = "https://facebook.com"
    },
    clickToAbout(){
      window.location = "/about"
    },
  }
}
</script>

<style>

</style>