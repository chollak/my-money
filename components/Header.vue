<template>
  <section>
    <div class="sticky-top mb-5">
      <nav class="nav justify-content-center bg-white">
        <router-link class="nav-link" to="/">Home</router-link>
        <router-link class="nav-link" to="/about">About</router-link>
      </nav>
      <div class="container-fluid">
        <div class="progress" style="height:5px">
          <div class="progress-bar" role="progressbar" v-bind:style="{ width:50 + '%' }"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
</style>