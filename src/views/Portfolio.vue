<template>
  <div class="portfolio">
    <b-container>
       <navbar></navbar>

    <b-row>
           <b-col></b-col>
            <b-col cols="10"><h1 class="h1-responsive">Portfolio</h1></b-col>
            <b-col></b-col>
         </b-row>

          <b-row class="form-group"></b-row>
          <b-row>
            <b-col cols="2"></b-col>
            <b-col cols="10"> <h2 class="p-responsive"> 
             Some of the noteworthy projects I have undertaken as part of my studies (TODO).
             </h2>
             </b-col>
          <b-col cols="2"></b-col>
          </b-row>
  </b-container>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  components: { "navbar": Navbar}
  
}
</script>

<style scoped>
.h1-responsive {
  text-align: center;
}
.p-responsive {
   font-size: calc(50% + 0.4vw + 0.4vh);
}
p {
  margin-bottom: 0;
}
</style>
