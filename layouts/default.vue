<template>
  <div>
    <NavBar />
    <main>
      <div class="container">
        <nuxt />
      </div>
    </main>
  </div>
</template>

<script>
  import NavBar from '../components/NavBar'

  export default {
    comments: {
      NavBar
    }
  }
</script>

<style>

</style>
