<template>
    <div class="footer">
        <div class="wrap box-footer">
            <a href="#">
                <img src="../assets/img/logo.svg" alt="">
            </a>
            <SocialLinks></SocialLinks>
        </div>
    </div>
</template>

<script>
    import SocialLinks from "@/components/SocialLinks";
    export default {
        name: "Footer",
        components:{
            SocialLinks,
        }
    }
</script>

<style scoped>
    .wrap {
        width: 100%;
        max-width: 1212px;
        margin: 0 auto;
        padding-left: 15px;
        padding-right: 15px;
        box-sizing: border-box;
    }
    .footer{
        padding-top: 20px;
        padding-bottom: 20px;
        background-color: #F7F7F7;
    }
    .box-footer{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }


</style>