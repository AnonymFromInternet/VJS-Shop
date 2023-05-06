<template>
    <div class="col">
        <img class="m-3 image image-left" src="../../../src/assets/images/t-shirts/t-shirt.jpg" alt="t-shirt">
    </div>

    <div class="col">
        <img class="m-3 image image-right" src="../../../src/assets/images/t-shirts/t-shirt-header.jpg" alt="t-shirt">

        <div class="flex-wrapper">
            <div class="link link-left">← For You</div>

            <div class="divider"></div>

            <div class="link link-up">↑ For You and Your Girlfriend</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'ImageHeaderComponent',
    }

</script>

<style scoped>
    .image {
        border-radius: 6px;
    }

    .image-left {
        width: 568px;
    }

    .link {
        display: inline;
        padding: 6px;
        text-align: center;
        border: 2px solid red;
        border-radius: 6px;


    }

    .link-left {
        margin-top: 42px;
    }

    .link-up {
        height: 38px;
    }

    .flex-wrapper {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 15px;
    }

    .divider {
        width: 306px;
        height: 1px;

        border: 1px solid #F82B2B;
        transform: rotate(9deg);

        margin-top: 18px;
    }
</style>