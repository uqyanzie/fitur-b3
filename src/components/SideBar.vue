<template>
    <div class="side-bar">
        <div class="container text-center d-block button-group mt-3 mb-3">
            <div class="row d-flex justify-content-between ">
                <button class="btn btn-tosca" type="button">Get Started</button>
                <button class="btn btn-white" type="button">Sign In</button>
            </div>
        </div>
        <div class="container text-center d-block mt-4 mb-3">
            <div class="row">
                <input type="search" class="search-bar" placeholder="Search...">
            </div>
        </div>
        <div class="container text-center d-block mt-4 mb-3">
            <div class="row">
                <div class="btn filter-bar">
                    <span>
                        Filter
                        <a class="float-end" data-bs-toggle="collapse" data-bs-target="#collapseFilter"
                            aria-expanded="false" aria-controls="collapseFilter">
                            <img src="../assets/filter.svg" style="width:20px">
                        </a>
                    </span>
                    <div class="collapse" id="collapseFilter">
                        <div class="separator"></div>
                        <div class="card card-body">
                            Sort by
                            <fieldset>
                                <input type="radio" id="sort-id">Date
                                <input type="radio" id="sort-id">Popular
                            </fieldset>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container text-center d-block mt-4 mb-3">
            <h6 class="head-category">Category</h6>
            <ul>
                <li>
                    <a href="" class="category-filter">
                        <div class="rect" id="makanan">
                            <div class="rect-backdrop">
                                <h5>Makanan</h5>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="" class="category-filter">
                        <div class="rect" id="restoran">
                            <div class="rect-backdrop">
                                <h5>Restoran</h5>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="" class="category-filter">
                        <div class="rect" id="penginapan">
                            <div class="rect-backdrop">
                                <h5>Penginapan</h5>
                            </div>
                        </div>
                    </a>
                </li>
                <li>
                    <a href="" class="category-filter">
                        <div class="rect" id="wisata">
                            <div class="rect-backdrop">
                                <h5>Wisata</h5>
                            </div>
                        </div>
                    </a>
                </li>
            </ul>
        </div>
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
        <div class="container d-block mt-4 mb-3">
            <div class="tags-container">
                <a class="tag-box" href="">
                    #liburan
                </a>
                <a class="tag-box" href="">
                    #pantai
                </a>
                <a class="tag-box" href="">
                    #penginapan nyaman
                </a>
                <a class="tag-box" href="">
                    #Liburan keluarga
                </a>
                <a class="tag-box" href="">
                    #Sunset
                </a>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style>
.side-bar {
    position: relative;
    top: 20px;
    width: 75%;
    margin: auto;
}

.button-group {
    position: relative;
    top: 10%;
    transform: translateY(50%);
    width: 100%;
}

.btn {
    padding: 3px 2px;
    border-radius: 15px;
    font-size: 12px;
    width: 45%;
}

.search-bar {
    background: #ECECEC;
    border-style: none;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 15px;
    font-size: 12px;
    padding: 10px 0 10px 15px;
    margin: 3 auto;
}

.search-bar:focus {
    border-style: none;
}

.btn-tosca {
    background: #309C9F;
    border-color: #309C9F;
    color: white;
}

.btn-tosca:active {
    border-color: #309C9F;
}

.btn-white {
    border-color: #309C9F;
}

.btn-white:active {
    background-color: #309C9F;
    border-color: #309C9F;
    color: white;
}

.filter-bar {
    border-radius: 15px;
    border-style: none;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    background: #ECECEC;
    width: 100%;
    text-align: left;
}

.filter-bar:hover {
    border-style: none;
    background: #ECECEC;
}

.filter-bar:active {
    border-style: none;
    background: #ECECEC;
}

.filter-bar>span {
    padding-left: 15px;
}

.filter-bar>span>a {
    padding-right: 15px;
}

.separator {
    margin: 10px auto;
    width: 85%;
    border-bottom: solid 1px black;
}

.collapse {
    height: 200px;
}

.card {
    margin: 10px 10px;
    padding: 0;
    background: #ECECEC;
    border-style: none;
}

.head-category {
    text-align: left;
}

.category-filter {
    text-decoration: none;
    color: #393a3a;
    width: 100%;
}



.rect {
    margin: 10px auto;
    padding: 0;
    display: block;
    border: solid 1px #393a3a;
    width: 100%;
    height: 50px;
    background-size: cover;
    place-items: center;
    border-style: none;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.rect:hover {
    scale: 1.05;
}

.rect:active {
    scale: 1.15;
}

.rect-backdrop {
    background-color: rgba(255, 255, 255, 0.025);
    -webkit-backdrop-filter: brightness(60%);
    backdrop-filter: brightness(60%);
    padding: 10px 0;
    height: 101%;
    width: 100%;
}

.rect-backdrop>h5 {
    color: white;
}

#makanan {
    background-image: url(../assets/makanan.jpg);
}

#restoran {
    background-image: url(../assets/restoran.jpg);
}

#penginapan {
    background-image: url(../assets/penginapan.jpg);
}

#wisata {
    background-image: url(../assets/wisata.jpg);
}

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

.tags-container {
    position: relative;
    right: 10%;
    height: 200px;
    width: 120%;
    padding: 10px;
}

.tag-box {
    display: inline-block;
    padding: 2px 4px;
    border-radius: 5px;
    text-decoration: none;
    font-size: 13px;
    border: solid 0.75px rgba(133, 133, 133, 0.671);
    color: rgba(133, 133, 133, 0.676);
    margin: 5px 10px;
}
</style>