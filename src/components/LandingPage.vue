<template>
<div>
    <Header/>
    <Article/>
    <RelatedResources/>
</div>
</template>

<script>
import Header from "@/components/Header.vue"
import Article from "@/components/Article.vue"
import RelatedResources from "@/components/RelatedResources.vue"
export default {
    name: "LandingPage",
    components: {Header, Article, RelatedResources}
}
</script>