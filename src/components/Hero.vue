<template>
  <div>
      <div class="background-hero">
          <Navbar />

          <div class="mb-5">
              <h1 class="display-4 fw-bold text-dark text-center mt-4">Gorgeous Code Snippets</h1>

              <p class="text-center mt-4">
                  With Snipper, create fully customizable code snippets in a matter of seconds
                  <br> right from your browser.
              </p>

              <Button  class="d-flex justify-content-center mt-4" />

              <p class="text-center mt-3">
                  No credit card required.
              </p>
              
              <div class="mt-5">
                  <img src="../assets/img/Snippet.png" alt="Image snippet" class="img-fluid d-flex justify-content-center aling-items-center">
              </div>
              
          </div>
      </div>
  </div>
</template>

<script>
import Navbar from './Navbar.vue'
import Button from './Button.vue'

export default {
    name: 'Hero',
    components: {
        Navbar,
        Button,
    }
}
</script>

<style scoped>
    .background-hero {
        background-image: url('../assets/img/Background.png');
        background-position: center center;
        background-repeat: no-repeat;
        background-size: cover;
        width: 100%;
        min-height: auto;
    }

    .mt-5 {
        margin-top: 5rem !important;
    }
</style>