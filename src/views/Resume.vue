<template>
  <div class="resume">
    <b-container>
    <navbar></navbar>

    <b-row>
          <b-col></b-col>
            <b-col cols="10"><h1 class="h1-responsive">Jack Edwards</h1></b-col>
            <b-col></b-col>
         </b-row>
         <b-row>
         <b-col></b-col>
            <b-col cols="10"><h3 class="h3-responsive">Student</h3></b-col>
            <b-col></b-col>
         </b-row>

          <b-row class="form-group"></b-row>
        

          <b-row>
            <b-col cols="3">
              <img src="../assets/dp.png" class="img-fluid" alt="Jack profile picture">
              </b-col>
            <b-col cols="9">
              <h2 class="h2-responsive">
             
             Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
             
             </h2>
              </b-col>
            

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
.h1-responsive, 
.h3-responsive {
  text-align: center;
}
</style>