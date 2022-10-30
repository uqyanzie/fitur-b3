<template>
  <div class="article-page d-flex">
    <ArticleNavbar></ArticleNavbar>
    <div class="col col-xl article">
      <div class="container">
        <ArticleTab></ArticleTab>
      </div>
      <div class="right-bar">
        <SideBar></SideBar>
      </div>
    </div>
  </div>
</template>

<script>
import ArticleNavbar from './ArticleNavbar.vue'
import ArticleTab from './ArticleTab.vue'
import SideBar from './SideBar.vue'
export default {
  name: 'App',
  components: {
    ArticleNavbar,
    ArticleTab,
    SideBar
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
  background: rgba(245, 245, 245, 1);
  display: flex;
}

.right-bar {
  width: 35%;
  border-radius: 50px 0 0 0;
  background: #fff;
  position: relative;
}
</style>
