<template>
    <div class="bg-white-smoke">
        <div class="pl-3 pt-3 small-article-heading"> Related Resources</div>
        <div class="p-3 d-flex justify-content-between flex-wrap pl-5 pr-5">
            <div>
                <img src="@/assets/Catalog.png" class="max-height">
                    <div> <b-button>Nut Catalog</b-button></div>

            </div>
            <div>
                <img src="@/assets/NutThreadSizing.jpg" width="50%" class="">
                  <div><b-button>How To Measure Thread Size</b-button></div>
            </div>
            <div>
                <img src="@/assets/NutsCollection.png" class="max-height">
                    <div><b-button >Nut Materials</b-button></div>
            </div>

        </div>
    </div>
</template>


<script>
export default {
    name: "RelatedResources"
}
</script>

<style scoped>
.image-caption {
color: black
}
.max-height {
    max-height: 200px
}
</style>