<template>

    <Header></Header>

    <Welcome></Welcome>

    <Content></Content>

    <News></News>
    
    <Footer></Footer>

</template>

<script>
import Footer from "@/components/Footer.vue";
import Header from "@/components/Header.vue";
import Content from "@/components/Content.vue";
import Welcome from "@/components/Welcome.vue";
import News from "@/components/News.vue";

export default {
    name: "App",
    components: {News, Welcome, Content, Header, Footer},


}
</script>

<style>
.text-block {
    position: relative;
    z-index: 1;
    color: white;
}
</style>