<template>
    <div class="team-item">
        <img :src="image">
        <div>
            <h3>{{name}}</h3>
            <p>{{desc}}</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "TeamItem",
        props: {
            image: {
                type: String,
                required: true,
            },
            name: {
                type: String,
                required: true,
            },
            desc: {
                type: String,
                required: true,
            },

        }

    }
</script>

<style scoped>

</style>