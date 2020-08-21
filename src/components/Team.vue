<template>
    <div class="team">
        <TeamItem v-for="item in teams"
                  :key="item"
                  v-bind="item"></TeamItem>
    </div>
</template>

<script>
    import TeamItem from "@/components/TeamItem";

    export default {
        name: "Team",
        data() {
            return {
                teams: [
                    {
                        image: require('../assets/img/client-1.png'),
                        name: "Vadim",
                        desc: "Managing Director",
                    },
                    {
                        image: require('../assets/img/client-2.png'),
                        name: "Sergey",
                        desc: "Technology Director",
                    },
                    {
                        image: require('../assets/img/client-3.png'),
                        name: "Andrey",
                        desc: "Front-end Developer",
                    },
                    {
                        image: require('../assets/img/client-4.png'),
                        name: "Alex",
                        desc: "Front-end Developer",
                    },
                    {
                        image: require('../assets/img/client-5.png'),
                        name: "Agneshka",
                        desc: "Mobile Developer",
                    },
                    {
                        image: require('../assets/img/client-6.png'),
                        name: "Dmitry",
                        desc: "Back-end Developer",
                    },
                    {
                        image: require('../assets/img/client-7.png'),
                        name: "Artyom",
                        desc: "Back-end Developer",
                    },
                    {
                        image: require('../assets/img/client-8.png'),
                        name: "Evgeny",
                        desc: "Product Designer",
                    },
                    {
                        image: require('../assets/img/client-9.png'),
                        name: "Tom",
                        desc: "Product Designer",
                    }
                ]
            }
        },
        components: {
            TeamItem,
        }
    }
</script>

<style scoped>
    .team {
        display: grid;
        grid-template: repeat(3, 1fr) / repeat(3, 1fr);
        grid-row-gap: 51px;
        padding-top: 20px;
    }

    .team-item {
        display: flex;
        justify-content: flex-start;
        align-items: center;
    }

    .team-item img {
        margin-right: 35px;
    }

    .team-item > div {
        flex-basis: calc(100% - 120px);
    }

    .team-item h3 {
        font-size: 28px;
        color: #202020;
        margin-bottom: 0;
        margin-top: 7px;
    }

    .team-item p {
        font-size: 14px;
        color: #B2B2B2;
    }
</style>