<template>
  <div class="article-page d-flex">
    <ArticleNavbar></ArticleNavbar>
    <div class="article col col-xl">
      <ArticleTab></ArticleTab>
    </div>
  </div>
</template>

<script>
import ArticleNavbar from './ArticleNavbar.vue'
import ArticleTab from './ArticleTab.vue';
export default {
  name: 'App',
  components: {
    ArticleNavbar,
    ArticleTab
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

.article {
  border-radius: 50px 0 0 0;
  background: #E5E5E5;
}
</style>
