<template>
  <div id="app">
   <Hero />
   <Article />
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Article from './components/Article.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Article
  }
}
</script>