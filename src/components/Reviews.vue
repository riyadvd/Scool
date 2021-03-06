<template>
  <div id="reviews">
        <h1>Reviews <span class="review-no">3</span></h1>
        <comment name="Ankit Jain" date="November 20,2020 at 11.23 AM" comment="The only class you'll ever need in marketing!" likes="256"/>
        <comment name="Mansi Bhalsera" date="December 01,2020 at 04:25 PM" comment="I'm so glad I found this class, I would've been so lost had I gone somewhere else. I found everything I needed in this one course." likes="149"/>
        <comment name="Sameer Khan" date="December 03,2020 at 08.23 AM" comment="I really liked this course because the mentor was someone who had actually done everything he taught!" likes="87"/>        
        <button class="review-btn desktop">See all reviews</button>
        <button class="review-btn comment-btn">See all Comments</button>
  </div>
</template>

<script>

import comment from './comment';


export default {
    name:"Reviews",
    components:{
        comment,
    }

}
</script>
