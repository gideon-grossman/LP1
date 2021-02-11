<template>
<div>
    <Header/>
    <Article/>
</div>
</template>

<script>
import Header from "@/components/Header.vue"
import Article from "@/components/Article.vue"
export default {
    name: "LandingPage",
    components: {Header, Article}
}
</script>