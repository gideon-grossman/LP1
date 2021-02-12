<template>
<div>
    <Header/>
    <Article/>
    <RelatedResources/>
    <Footer/>
</div>
</template>

<script>
import Header from "@/components/Header.vue"
import Article from "@/components/Article.vue"
import RelatedResources from "@/components/RelatedResources.vue"
import Footer from "@/components/Footer.vue"

export default {
    name: "LandingPage",
    components: {Header, Article, RelatedResources, Footer}
}
</script>