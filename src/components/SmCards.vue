<template>
    <div class="container text-center d-block mt-4 mb-3">
        <h6 class="head-category">Popular on Geowisata!</h6>
        <ul>
            <li class="card-list mt-3 mb-3">
                <a href="" class="article-card">
                    <div class="sm-card">
                        <div class="card-body d-flex">
                            <img src="../assets/empty-pic.svg" alt="" style="width:50px; margin:8px">
                            <div class="flex-item article-preview">
                                <h6>Article Title</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque nisi, consequatur
                                    quaerat quam asperiores eveniet dolorem deserunt laboriosam veritatis, mollitia
                                    quidem enim porro quo quis quae eligendi repudiandae quia. Ab.</p>
                            </div>
                        </div>
                    </div>
                </a>
            </li>
            <li class="card-list mt-4 mb-3">
                <a href="" class="article-card">
                    <div class="sm-card">
                        <div class="card-body d-flex">
                            <img src="../assets/empty-pic.svg" alt="" style="width:50px; margin:8px">
                            <div class="flex-item article-preview">
                                <h6>Article Title</h6>
                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum illo, eligendi
                                    quas tenetur odit, doloribus asperiores, soluta repellat aut cum voluptatibus
                                    veritatis. Quis optio ab iste, reprehenderit numquam placeat nostrum.</p>
                            </div>
                        </div>
                    </div>
                </a>
            </li>
            <li class="card-list mt-4 mb-3">
                <a href="" class="article-card">
                    <div class="sm-card">
                        <div class="card-body d-flex">
                            <img src="../assets/empty-pic.svg" alt="" style="width:50px; margin:8px">
                            <div class="flex-item article-preview">
                                <h6>Article Title</h6>
                                <p>Lorem ipsum dolor sit amet</p>
                            </div>
                        </div>
                    </div>
                </a>
            </li>
        </ul>
    </div>
</template>
<script>
export default {

}
</script>
<style>
.article-card {
    text-decoration: none;
    color: #393a3a;
    width: 100%;
}

.sm-card {
    margin: auto;
    position: relative;
    display: flex;
    width: 110%;
    right: 10px;
    height: 80px;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.article-preview {
    padding: 15px 5px 15px 0;
    text-align: left;
    margin: 10 5px;
    line-height: normal;
    overflow: hidden;
}

.article-preview>p {
    font-size: 12px;
    margin: 0;
    height: 15px;
    overflow: hidden;
}
</style>