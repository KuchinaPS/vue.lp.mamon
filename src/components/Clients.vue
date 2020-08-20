<template>
    <div class="clients">
        <div class="clients-item">
            <img src="../assets/img/logo-lightspeed.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-trvl.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-spider-strategies.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-tripadvisor.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-shutterfly.svg" alt="">
        </div>
        <div class="clientst-item">
            <img src="../assets/img/logo-decos.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-tiqets.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-hotelchamp.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-flitsmeister.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-sap.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-redkix.svg" alt="">
        </div>
        <div class="clients-item">
            <img src="../assets/img/logo-nos.svg" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: "Clients"
    }
</script>

<style scoped>

    .clients {
        display: grid;
        grid-template: repeat(2, 1fr) /repeat(4, 25%);
        grid-row-gap: 44px;
        text-align: center;
        padding-top: 0;
    }

</style>