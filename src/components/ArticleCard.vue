<template>
    <div class="card w-100">
        <div class="card-body d-flex ">
            <img class="flex-item preview-pict" src="../assets/image.svg" alt="">
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
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam
                    veroquos, saepe atque quae nostrum numquam sequi quis minus laboriosam, repellat, ipsum
                    voluptatem laudantium perspiciatis facilis. Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Esse, nesciunt vitae nemo doloremque reprehenderit eaque quos numquam iste et quam dolores totam,
                    modi doloribus assumenda delectus velit facilis vel accusamus.
                </p>
                <a href="#" class="card-link">Card link</a>
                <a href="#" class="card-link">Another link</a>
            </div>
        </div>
    </div>
</template>

<style scoped>
.card {
    border-radius: 0;
    border: 0 0 1px 1px;
    box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px 0px, rgba(0, 0, 0, 0.23) 0px 3px 6px 0px;
    margin: 25px 0 50px 0;
    max-height: 250px;
}

.card-body {
    height: inherit;
}

.card-text {
    max-width: 80%;
    max-height: 100px;
}

.flex-item {
    margin-left: 30px;
}

.flex-item>p {
    overflow: hidden;
}

.preview-pict {
    max-width: 150px;
    margin-right: 5%;
}
</style>