<template>
    <div class="side-bar">
        <div class="container text-center d-block button-group mt-3 mb-3">
            <div class="row d-flex justify-content-between">
                <button class="btn btn-tosca" type="button">Get Started</button>
                <button class="btn btn-white" type="button">Sign In</button>
            </div>
        </div>
        <div class="container text-center d-block mt-4 mb-3">
            <div class="row">
                <input type="search" class="search-bar" placeholder="Search...">
            </div>
        </div>
        <div class="container text-center d-block mt-3 mb-3">
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
    </div>
</template>

<script>

</script>

<style>
.side-bar {
    position: relative;
    top: 20px;
    width: 90%;
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
    height: 150px;
}

.card {
    margin: 10px 10px;
    padding: 0;
    background: #ECECEC;
    border-style: none;
}
</style>