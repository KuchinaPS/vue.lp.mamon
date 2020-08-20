<template>
    <div class="services-item">
        <div class="services_img">
            <img v-bind:src="image" alt="" />
        </div>
        <div class="services_text">
            <h3>{{article}}</h3>
            <p>{{text}}</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "ServicesItem",
        props:{
            image: {
                type: String,
                required: true,
            },
            article:{
                type: String,
                required: true,
            },
            text:{
                type: String,
                required: true,
            }
        }
    }
</script>

<style scoped>
    .services-item {
        display: flex;
        justify-content: flex-start;
        align-items: center;
    }

    .services_img {
        flex-basis: 165px;
        text-align: center;
    }

    .services_text {
        flex-basis: calc(80% - 165px);
    }
    .services-item h3 {
        font-size: 28px;
        font-weight: 400;
        margin-bottom: 17px;
        margin-top: 0;
    }

    .services-item p {
        font-size: 14px;
        color: #B2B2B2;
        line-height: 1.5;
    }
</style>