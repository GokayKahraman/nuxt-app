<template>
  <div >
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet nobis blanditiis asperiores quas, officia omnis itaque necessitatibus voluptatem. Minus vel laboriosam quod consequuntur architecto doloribus magnam nemo, ex aut ut.
  </div>
</template>

<script>
const axios = require("axios")
export default {
    mounted: function() {
    axios.get("https://animechan.vercel.app/api/quotes")
      
    },
  
} 
</script>

<style>

</style>
