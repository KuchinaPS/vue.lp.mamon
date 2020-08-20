<template>
        <div class="header">
            <a href="#" class="logo">
                <span class="logo_img"></span>
                <span class="logo_text">mamon</span>
            </a>
           <Navigation></Navigation>
        </div>

</template>

<script>
    import Navigation from "@/components/Navigation";

    export default {
        name:"Header",
        components: {  //Components
            Navigation,
        }
    }
</script>

<style>
    .header {
        width: 100%;
        max-width: 1180px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-left: 15px;
        padding-right: 15px;
        padding-top: 30px;
        box-sizing: border-box;
        font-weight: 700;
    }

    .logo {
        display: flex;
        align-items: center;
        text-decoration: none;
    }

    .logo_img {
        display: block;
        width: 58px;
        height: 58px;
        background-image: url("../assets/img/logo.svg");
        margin-right: 20px;
    }

    .logo_text {
        font-size: 24px;
        color: #202020;
    }

</style>