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

    <div class="pl-3 bg-white-smoke article-grey-strip">
        <div class="pl-3 pt-3 small-article-heading"> How to Select a Nut</div>
        <iframe class="article-photo pr-3" width="280" height="157" src="https://www.youtube.com/embed/I4PcIY-Mu58" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <p class="pl-3"> The nut should always be stronger than the bolt, so when using higher strength bolts, such as metric class 10.9, make sure to use the correct, corresponding nut. In this case, a class 10 nut would be correct. Stronger nuts may be used with lower strength bolts without any problems.</p>
        <b-button class="ml-3 pl-3">View More</b-button>

    </div>

    <div class="pl-3">
        <div class="pl-3 pt-3 small-article-heading"> US Nut Size Table</div>
        <p class="pl-3">                 <img class="article-photo"  width="30%" src="@/assets/NutDimensions.png">
Our nuts are manufactured from superior materials resistant to rust and fracture with high tensile and yield strength to ensure they last through harsh weather and many years. Charts like the one below are helpful in choosing the correct nut for your application. Whichever size you need, we have it.</p>

<b-button class="ml-3 pl-3 mb-2">View Product Page</b-button>

    <b-table
      :items="items"
      :fields="fields"
      responsive="sm"
      bordered
    >
      <template v-slot:thead-top>
        <b-tr>
          <b-th class="no-border"></b-th>
          <b-th variant="secondary" colspan="2">E</b-th>
          <b-th variant="secondary" colspan="3">F</b-th>
          <b-th variant="secondary" colspan="2">G</b-th>
          <b-th variant="secondary" colspan="3">H</b-th>
          <b-th variant="secondary" colspan="2">L</b-th>
          
        </b-tr>
      <b-tr class="bg-yellow">
          <b-th class="no-border bg-white"></b-th>
          <b-th  colspan="2">Body Dia.</b-th>
          <b-th colspan="3">Width Across Flats</b-th>
          <b-th colspan="2">Width Across Corners</b-th>
          <b-th colspan="3">Height</b-th>
          <b-th colspan="2">Thread Lengths for Screw Lengths</b-th>
          
          <!-- <b-th variant="danger">Type 3</b-th> -->
        </b-tr>
      </template>
      
    </b-table>

    </div>
</div>
</template>

<script>
export default {
    name: "Article",
    data() {
         return {
             items: [
             {
                 "nominalSize":1/4,
                 "maxBodyDiam": 0.2500,
                 "minBodyDiam": 0.2450, 
                 "basicFlatsWidth":7/16, 
                 "maxFlatsWidth":0.438, 
                 "minFlatsWidth":0.428,
                 "maxCornersWidth":0.505,
                 "minCornersWidth":0.488,
                  "basicHeight":5/32, 
                  "maxHeight":0.163, 
                  "minHeight":0.150,
                  "basicThreadLengthUnderSix":0.750,
                  "basicThreadLengthOverSix":1.000
             },
             {
                 "nominalSize":5/16,
                 "maxBodyDiam": 0.3125,
                 "minBodyDiam": 0.3065, 
                 "basicFlatsWidth":1/2, 
                 "maxFlatsWidth":0.500, 
                 "minFlatsWidth":0.489,
                 "maxCornersWidth":0.577,
                 "minCornersWidth":0.577,
                  "basicHeight":13/64, 
                  "maxHeight":0.211, 
                  "minHeight":0.195,
                  "basicThreadLengthUnderSix":0.875,
                  "basicThreadLengthOverSix":1.125
             }             
            
             ],
             fields: [{key: "nominalSize", "label": "Nominal Size or Basic Screw Dia."},
             {key: "maxBodyDiam", "label": "Max."},
             {key: "minBodyDiam", "label": "Min."},
             {key: "basicFlatsWidth", "label": "Basic"},
             {key: "maxFlatsWidth", "label": "Max."},
             {key: "minFlatsWidth", "label": "Min."},
             {key: "maxCornersWidth", "label": "Max"},
             {key: "minCornersWidth", "label": "Min."},
             {key: "basicHeight", "label": "Basic"},
             {key: "maxHeight", "label": "Max."},
             {key: "minHeight", "label": "Min."},
             {key: "basicThreadLengthUnderSix", "label": "Basic < 6 inches"},
             {key: "basicThreadLengthOverSix", "label": "Basic > 6 inches"}]
         }
    }
}
</script>

<style scoped>
.article-photo {
    float: right;

}
.article-section {
    min-height: 300px;
}

.article-grey-strip {
    min-height:280px;
}

.no-border{
    border-style: none
}
</style>
