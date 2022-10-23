<template>
    <div class="container article-list justify-content-start" style="width: fit-content">
        <ul>
            <li>
                <ArticleCard></ArticleCard>
            </li>
            <li>
                <ArticleCard></ArticleCard>
            </li>
            <li>
                <ArticleCard></ArticleCard>
            </li>
            <li>
                <ArticleCard></ArticleCard>
            </li>
        </ul>
    </div>
</template>

<script>
import ArticleCard from './ArticleCard.vue'

export default {
    name: 'App',
    components: {
        ArticleCard
    }
}
</script>

<style>
.article-list {
    display: flex;
    margin-right: 30px;
}

ul {
    list-style: none;
    margin: 0;
    padding: 0;
}
</style>