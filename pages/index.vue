<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title mb-5">NuxtJS App Starter</h1>
      <h3 class="subtitle mb-5">This is the home / index page.</h3>
      <div class="links mb-5">
        <n-link to="/about">Go to about page</n-link>
        <br /><br />
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Read the documentation
        </a>
      </div>
      <div>
        <p>
          <small><em>To be continued...</em></small>
        </p>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
