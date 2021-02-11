<template>
<div align="left">
    <div class="pl-3 pb-2">
        <h1 class="pl-3 pt-3">  NUTS</h1>
        <div class="pl-1"> 2 Minute Read</div>
    </div>
    <div class="pl-3 article-section">
    <p class="pl-3 pt-1">
        <img class="article-photo"  width="15%" src="https://i.stack.imgur.com/YA5ZH.jpg">
        A nut is a type of fastener with a threaded hole. Nuts are almost always used in conjunction with a mating bolt to fasten multiple parts together. The two partners are kept together by a combination of their threads' friction (with slight elastic deformation), a slight stretching of the bolt, and compression of the parts to be held together.
        In applications where vibration or rotation may work a nut loose, various locking mechanisms may be employed: lock washers, jam nuts, specialist adhesive thread-locking fluid such as Loctite, safety pins (split pins) or lockwire in conjunction with castellated nuts, nylon inserts (nyloc nut), or slightly oval-shaped threads.
    </p>
    </div>

    <div class="pl-3 bg-grey">
        <div class="pl-3 pt-3 small-article-heading"> How to Select a Nut</div>
        <iframe class="article-photo" src="https://www.youtube.com/watch?v=I4PcIY-Mu58"></iframe>
        <p class="pl-3"> The nut should always be stronger than the bolt, so when using higher strength bolts, such as metric class 10.9, make sure to use the correct, corresponding nut. In this case, a class 10 nut would be correct. Stronger nuts may be used with lower strength bolts without any problems.</p>
        <b-button class="pl-3">View More</b-button>

    </div>
</div>
</template>

<script>
export default {
    name: "Article"
}
</script>

<style scoped>
.article-photo {
    float: right;

}
.article-section {
    min-height: 300px;
}

.small-article-heading {
    font-size: 24px;
    font-weight: bold;
}
</style>
