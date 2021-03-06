<template>
  <div id="comment">
        <div class="review">
            <div class="profile"></div>
            <div class="review-des">
                <h3>{{ name }} <span class="date">{{ date }}</span></h3>
               
            </div>
            
        </div>
        <div class="comm">
          <div class="comment">{{ comment }}</div>
          <p class="likes"><i class="fa fa-heart-o" aria-hidden="true"></i>{{ likes }}</p>
        </div>
  </div>
</template>

<script>

export default {
  name: 'comment',
  props: {
    name: String,
    comment: String,
    likes: String,
    date: String,
  }
}
</script>
