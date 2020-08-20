<template>
    <ul class="social">
        <li><a href="#" target="_blank" class="link link_git"></a></li>
        <li><a href="#" target="_blank" class="link link_be"></a></li>
        <li><a href="#" target="_blank" class="link link_in"></a></li>
        <li><a href="#" target="_blank" class="link link_cp"></a></li>
    </ul>
</template>

<script>
    export default {
        name: "SocialLinks"
    }
</script>

<style scoped>
    .social{
        display: flex;
        list-style: none;
        padding-left: 0;
        background-color: #5528FF;
    }
    .social>li{
        margin-left: 40px;
        padding-left: 10px;
        position: relative;
    }

    .link{
        content: "";
        position: absolute;
        width: 24px;
        height: 24px;
        background-repeat: no-repeat;
        background-size: contain;
    }
    .link_git{
        background-image: url("../assets/img/github_git_icon_145985.svg");
    }
    .link_be{
        background-image: url("../assets/img/Behance_Solid_icon-icons.com_71813.svg");
    }
    .link_in{
        background-image: url("../assets/img/LINKEDIN_icon-icons.com_62683.svg");
    }
    .link_cp{
        background-image: url("../assets/img/codepen_icon_128901.svg");
    }
    .link svg{
        color: #B2B2B2;
    }
</style>