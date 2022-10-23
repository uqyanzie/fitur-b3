<template>
    <div class="container article-list justify-content-start" style="width: fit-content">
        <ul>
            <li>
                <div class="card w-100">
                    <div class="card-body d-flex justify-content-between">
                        <img class="flex-item" src="../assets/image.svg" alt="">
                        <div class="flex-item">
                            <h6 class="card-title">
                                <span>
                                    <img src="../assets/creator.png" alt="">
                                </span>
                                Creator Name
                                <span style="float : right">
                                    <img src="../assets/save.svg" alt="">
                                    <img src="../assets/report.svg" alt="">
                                </span>
                            </h6>
                            <h4 class="card-subtitle mb-2">Article Title</h4>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam vero
                                quos, saepe atque quae nostrum numquam sequi quis minus laboriosam, repellat, ipsum
                                voluptatem laudantium perspiciatis facilis. Numquam voluptate quod nesciunt.</p>
                            <a href="#" class="card-link">Card link</a>
                            <a href="#" class="card-link">Another link</a>
                        </div>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</template>

<style>
.article-list {
    display: flex;
    margin: 0;
}

.card {
    border-radius: 0;
    border: 0 0 1px 1px;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px 0px, rgba(0, 0, 0, 0.23) 0px 3px 6px 0px;
}

ul {
    list-style: none;
}

.flex-item {
    padding: 30px;
}
</style>