<template lang="">
    <div class="card_rating">
     <img v-for="i in fullStars" :key="'full-star-' + i" src="../assets/star.svg">
     <img v-if="hasHalfStar" key="half-star" src="../assets/star_half.svg">
     <img v-for="i in emptyStars" :key="'empty-star-' + i" src="../assets/star_grey.svg">
    </div>
</template>
<script>

export default {
    props: ['rate'],
  data(){
    return {rating: this.rate}
  },
  computed: {
    fullStars() {
      return Math.floor(this.rating / 2);
    },
    hasHalfStar() {
      return this.rating % 2 !== 0;
    },
    emptyStars() {
      const maxRating = 5;
      return maxRating - this.fullStars - (this.hasHalfStar ? 1 : 0);
    }
  },
};

function star_check (rating){
var total_full_stars = Math.floor( rating / 2);
var total_half_stars = Math.floor( rating % 2);
return [total_full_stars, total_half_stars];
}
console.log(star_check(8));
function star_init(stars){
    for (let i = 1; i <= stars[i]; i++) {
    }
}
</script>
<style lang="">
</style>