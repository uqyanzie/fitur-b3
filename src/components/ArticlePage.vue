<template>
  <div class="article-page d-flex">
    <ArticleNavbar></ArticleNavbar>
    <div class="col col-xl article">
      <div class="container article-tab">
        <nav>
          <div class="nav nav-tabs" id="nav-tab" role="tablist">
            <button class="nav-link active" id="nav-for-you-tab" data-bs-toggle="tab" data-bs-target="#nav-for-you"
              type="button" role="tab" aria-controls="nav-for-you" aria-selected="true">For you</button>
            <button class="nav-link" id="nav-following-tab" data-bs-toggle="tab" data-bs-target="#nav-following"
              type="button" role="tab" aria-controls="nav-following" aria-selected="false">Following</button>
            <button class="nav-link" id="nav-bookmark-tab" data-bs-toggle="tab" data-bs-target="#nav-bookmark"
              type="button" role="tab" aria-controls="nav-contact" aria-selected="false">Bookmarked</button>
          </div>
        </nav>
        <div class="tab-content" id="nav-tabContent">
          <div class="tab-pane fade show active" id="nav-for-you" role="tabpanel" aria-labelledby="nav-for-you-tab"
            tabindex="0">
            <h1>Home</h1>
            <ArticleList></ArticleList>
          </div>
          <div class="tab-pane fade" id="nav-following" role="tabpanel" aria-labelledby="nav-following-tab"
            tabindex="0">
            <h1>Profile</h1>
            <ArticleList></ArticleList>
          </div>
          <div class="tab-pane fade" id="nav-bookmark" role="tabpanel" aria-labelledby="nav-bookmark-tab" tabindex="0">
            <h1>Contact</h1>
            <ArticleList></ArticleList>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ArticleNavbar from './ArticleNavbar.vue'
import ArticleList from './ArticleList.vue'
export default {
  name: 'App',
  components: {
    ArticleNavbar,
    ArticleList
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

.article-tab {
  position: relative;
  left: 2%;
  top: 3%;
}
</style>
