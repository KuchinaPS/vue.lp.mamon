<template>
    <nav>
        <ul class="nav">
            <li><a href="#">Services</a></li>
            <li><a href="#">Clients</a></li>
            <li><a href="#">Our team</a></li>
            <li>
                <button type="button" class="nav_btn">Contact Us</button>
            </li>
        </ul>
    </nav>
</template>

<script>
    export default {
        name: "Navigation"
    }
</script>

<style scoped>

    .nav {
        list-style: none;
        display: flex;
        justify-content: flex-start;
        font-size: 14px;
        align-items: center;
    }

    .nav > li {
        margin-left: 37px;
    }

    .nav > li > a {
        text-decoration: none;
        color: #202020;
    }

    .nav_btn {
        background-color: #5528FF;
        border-radius: 5px;
        padding: 6px 14px;
        color: #fff;
        border: none;
        font-weight: 700;
    }

</style>