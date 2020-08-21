<template>
    <div class="clients">
        <div class="clients-item" v-for="item in image" :key="item">
            <img :src="item.img" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: "Clients",
        data() {
            return {
                image: [
                    {
                        img: require('../assets/img/logo-lightspeed.svg')
                    },
                    {
                        img: require('../assets/img/logo-trvl.svg')
                    },
                    {
                        img: require('../assets/img/logo-spider-strategies.svg')
                    },
                    {
                        img: require('../assets/img/logo-tripadvisor.svg')
                    },
                    {
                        img: require('../assets/img/logo-shutterfly.svg')
                    },
                    {
                        img: require('../assets/img/logo-decos.svg')
                    },
                    {
                        img: require('../assets/img/logo-tiqets.svg')
                    },
                    {
                        img: require('../assets/img/logo-hotelchamp.svg')
                    },
                    {
                        img: require('../assets/img/logo-flitsmeister.svg')
                    },
                    {
                        img: require('../assets/img/logo-sap.svg')
                    },
                    {
                        img: require('../assets/img/logo-redkix.svg')
                    },
                    {
                        img: require('../assets/img/logo-nos.svg')
                    },
                ],
            }


        },
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