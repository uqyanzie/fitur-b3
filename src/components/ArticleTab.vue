<template>
    <div class="container article-tab">
        <nav>
            <div class="nav nav-tabs" id="nav-tab" role="tablist">
                <button class="nav-link" id="nav-for-you-tab" data-bs-toggle="tab" data-bs-target="#nav-for-you"
                    type="button" role="tab" aria-controls="nav-for-you" aria-selected="true">For you</button>
                <button class="nav-link" id="nav-following-tab" data-bs-toggle="tab" data-bs-target="#nav-following"
                    type="button" role="tab" aria-controls="nav-following" aria-selected="false">Following</button>
            </div>
        </nav>
        <div class="tab-content" id="nav-tabContent">
            <div class="tab-pane fade show active" id="nav-for-you" role="tabpanel" aria-labelledby="nav-for-you-tab"
                tabindex="0">
                <ArticleList></ArticleList>
            </div>
            <div class="tab-pane fade" id="nav-following" role="tabpanel" aria-labelledby="nav-following-tab"
                tabindex="0">
                <ArticleList></ArticleList>
            </div>
            <div class="tab-pane fade" id="nav-bookmark" role="tabpanel" aria-labelledby="nav-bookmark-tab"
                tabindex="0">
                <ArticleList></ArticleList>
            </div>
        </div>
    </div>
</template>

<script>
import ArticleList from './ArticleList.vue'

export default {
    name: 'App',
    components: {
        ArticleList
    }
}
</script>

<style scoped>
.article-tab {
    position: relative;
    left: 2%;
    top: 3%;
    border: none;
}

#nav-tab {
    width: 90%;
    border-bottom: solid 1.2px black;
}


.nav-link {
    color: #000;
    background-color: rgba(245, 245, 245, 1);
    border-top: 0;
    border-bottom: solid 1px black;
}

.active {
    background-color: rgba(245, 245, 245, 1);
}


.nav-link:active {
    background-color: rgba(245, 245, 245, 1);
    border-bottom: solid 1.5px black;
    color: rgba(0, 0, 0, 1);
}

.nav-link:focus {
    background-color: rgba(245, 245, 245, 1);
    border-bottom: solid 1.5px black;
    color: #000;
}

.nav-link:hover {
    background-color: inherit;
    border-bottom: solid 1.5px black;
    color: #000;
}
</style>