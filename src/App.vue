<template>
    <div id="app">
        <Header></Header>
        <Promo></Promo>
        <MainPage></MainPage>
        <Footer></Footer>
    </div>
</template>

<script>
    import Header from "@/components/Header";
    import Promo from "@/components/Promo";
    import MainPage from "@/components/Main-page";
    import Footer from "@/components/Footer";

    export default {
        name: "App",
        components: {
            Header,
            Promo,
            MainPage,
            Footer,
        }
    };
</script>
<style>
    body {
        font-family: 'Ubuntu', sans-serif;
    }
</style>