<template>
    <div id="app">
        <Header></Header>
        <main class="page">
            <Banner></Banner>
            <WhyWe></WhyWe>
            <AboutUs></AboutUs>
            <Contacts></Contacts>
        </main>
        <Footer></Footer>
    </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import AboutUs from '@/components/AboutUs.vue';
import WhyWe from '@/components/WhyWe.vue';
import Contacts from '@/components/Contacts.vue';
import Footer from '@/components/Footer.vue';


export default {
    components: {
        Header,
        Banner,
        AboutUs,
        WhyWe,
        Contacts,
        Footer,
    },
};
</script>

<style lang="scss">
    @import "assets/scss/style.scss";
</style>
