<template>
  <div id="app">
    <ArticlePage></ArticlePage>
    <PageFooter></PageFooter>
  </div>
</template>

<script>
import PageFooter from './components/PageFooter.vue'
import ArticlePage from './components/ArticlePage.vue'
export default {
  name: 'App',
  components: {
    ArticlePage,
    PageFooter
  }
}
</script>

<style>
#app {
  margin: 0;
}
</style>
