<template>
    <div class="page">
        <div class="wrap">
            <h1 class="title-main">We're an independent development agency.</h1>
            <p class="text-main">We understand the intricacies of web development inside-out. That's why we build
                rock-solid Mobile and Web
                applications enriched with user-centered visual experiences.</p>
            <button type="button" class="button">Contact Us</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Promo"
    }
</script>

<style scoped>
    .page {
        padding-top: 83px;
        padding-bottom: 100px;
        position: relative;
    }

    .page h2 {
        position: absolute;
        top: -24px;
        font-size: 14px;
        font-weight: 300;
        background-color: #fff;
        padding: 5px 15px;
        color: #C2C2C2;
    }

    .wrap {
        width: 100%;
        max-width: 1180px;
        margin: 0 auto;
        padding-left: 15px;
        padding-right: 15px;
        box-sizing: border-box;
    }

    .title-main {
        font-size: 56px;
        color: #202020;
        font-weight: 700;
    }

    .title-main {
        font-size: 55px;
        color: #202020;
        font-weight: 700;
        letter-spacing: 0.8px;
        margin-bottom: 0.4em;
    }

    .text-main {
        font-size: 32px;
        line-height: 1.6;
        color: #4F4F4F;
        max-width: 746px;
        margin-bottom: 2em;

    }

    .button {
        background-color: #5528FF;
        border-radius: 10px;
        padding: 16px 60px;
        color: #fff;
        border: none;
        font-size: 24px;
    }

</style>