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
            <b-col></b-col>
           <b-col cols="10"> <h2 class="h2-responsive">
             
             Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
             
             </h2></b-col>
          <b-col></b-col>
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
