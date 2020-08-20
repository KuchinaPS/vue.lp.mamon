<template>
    <div class="services">
        <ServicesItem :image="require('../assets/img/smartphone.svg')"
                      article="Mobile Development"
                      text="We develop mobile apps for all contemporary
                    mobile platforms. Mamon team builds
                   native and cross-platform solutions."></ServicesItem>
        <ServicesItem :image="require('../assets/img/monitor.svg')"
                      article="Web Development"
                      text="Mamon offers full range of services from various
                           CMS and frameworks based websites to complex
                           ERP/CRM solutions and e-commerce stores."></ServicesItem>
        <ServicesItem :image="require('../assets/img/layers.svg')"
                      article="Product Design"
                      text="We create design given the product audience,
                            goal, business domain, technology and
                            the platform for the solution."></ServicesItem>
        <ServicesItem :image="require('../assets/img/test.svg')"
                      article="Quality Assurance"
                      text="Our QA team ensures high standard of
                            quality of products delivered."></ServicesItem>
    </div>
</template>

<script>
    import ServicesItem from "@/components/ServicesItem";

    export default {
        name: "Services",
        components: {
            ServicesItem,
        }
    }
</script>

<style scoped>
    .services {
        display: grid;
        grid-template: repeat(2, 1fr)/50% 50%;
        grid-row-gap: 38px;
    }

</style>