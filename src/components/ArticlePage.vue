<template>
  <div class="article-page d-flex">
    <ArticleNavbar></ArticleNavbar>
    <div class="col-11 bg-white article">
    </div>
  </div>
</template>

<script>
import ArticleNavbar from './ArticleNavbar.vue'
//import PageFooter from './PageFooter.vue'
export default {
  name: 'App',
  components: {
    ArticleNavbar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.article-page {
  background-color: #309C9F;
  height: 200vh;
  margin: 0;
}

@media screen {}

.article {
  border-radius: 100px 0 0 0;
}
</style>
