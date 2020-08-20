<template>
    <div class="page page-top">
        <div class="wrap">
            <h2>OUR SERVICES</h2>
            <Services></Services>
        </div>
        <div class="page page-top">
            <div class="wrap">
                <h2>OUR CLIENTS</h2>
                <Clients></Clients>
            </div>
        </div>
        <div class="page page-top">
            <div class="wrap">
                <h2>OUR TEAM</h2>
                <Team></Team>
            </div>
        </div>
    </div>
</template>

<script>
    import Services from "@/components/Services";
    import Clients from "@/components/Clients";
    import Team from "@/components/Team";

    export default {
        name: "MainPage",
        components: {
            Services,
            Clients,
            Team
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

    .page {
        padding-top: 85px;
        padding-bottom: 100px;
        position: relative;
    }
    .page:last-child{
        padding-bottom: 0;
    }
    .page-top {
        border-top: 1px solid #C2C2C2;
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
</style>