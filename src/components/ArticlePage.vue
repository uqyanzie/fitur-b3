<template>
  <div class="article-page d-flex">
    <ArticleNavbar></ArticleNavbar>
    <div class="col col-xl article">
      <ArticleTab></ArticleTab>
      <div class="right-bar">
        <div class="container side-bar">
          <div class="container text-center d-grid gap-3 button-group">
            <div class="row ">
              <button class="col btn" type="button">Button</button>
              <button class="col btn" type="button">Button</button>
            </div>
            <div class="row">
              <button class="col btn btn-primary" type="button">Button</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ArticleNavbar from './ArticleNavbar.vue'
import ArticleTab from './ArticleTab.vue'
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
  display: flex;
}

.right-bar {
  width: 35%;
  border-radius: 50px 0 0 0;
  background: #fff;
  position: relative;
}

.button-group {
  position: relative;
  top: 10%;
  transform: translateY(50%);
  padding: 20px;
}

.btn {
  padding: 1px 4px;
  margin: 5px;
  border-radius: 100px;
}
</style>
