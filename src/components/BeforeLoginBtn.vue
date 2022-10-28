<template >
    <div class="container text-center d-block button-group mt-3 mb-3">
        <div class="row d-flex justify-content-between ">
            <button class="btn btn-tosca" type="button">Get Started</button>
            <button class="btn btn-white" type="button">Sign In</button>
        </div>
    </div>
</template>
<script>

</script>
<style>
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
</style>