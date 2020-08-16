<template>
  <section>
    <Header />
    <main class="container">
      <div>
        <h1 class="title">
          Kyle McMaster
        </h1>
        <!-- <Skills /> -->
        <Languages />
        <Frameworks />
      </div>
    </main>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 93vh;
  /* display: flex; */
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  /* display: block; */
  font-weight: 200;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
