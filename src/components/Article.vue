<template>
  <div>
      <article class="p-4">
          <div class="container">
              <div class="row">
                  <div class="col-md-7 col-sm-12-col-lg-7 col-xl-7 col-xxl-7 mt-5">
                      <h2 class="fw-bold text-dark">A fully customizable code snippet
                        <br> editor</h2>

                      <p class="mt-4">
                          Fully customize the color scheme of your code snippet, or use our
                          <br> own premade color schemes. Export your code snippets in JPG, PDF,
                          <br> PNG, or any of the other 10+ common extensions.
                      </p>

                      <Button class="mt-4" />
                  </div>

                  <div class="col-md-5 col-sm-12 col-lg-5 col-xl-5 col-xxl-5 mt-4">
                    <img src="../assets/img/Customizable.png" alt="Customizable image" class="img-fluid">
                  </div>

                  <Footer />
              </div>
          </div>
      </article>
  </div>
</template>

<script>
import Button from './Button.vue'
import Footer from './Footer.vue'

export default {
    name: 'Article',
    components: {
        Button,
        Footer
    }
}
</script>

<style scoped>
    .mt-5 {
        margin-top: 7rem !important;
    }
</style>