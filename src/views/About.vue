<template>
  <div class="about">
    <b-container>
      <navbar></navbar>

    <b-row>
           <b-col></b-col>
            <b-col cols="10"><h1 class="h1-responsive">About</h1></b-col>
            <b-col></b-col>
   </b-row>

          <b-row class="form-group"></b-row>

   <b-row> 
     <b-col cols="2"></b-col>    
         <b-col cols="8">
              <p class="p-responsive">I grew up on the South Coast of NSW just outside of Bega, after I finished high school I moved to Wollongong
                 (my friends were off to university there) and worked in various jobs for a few years. I have always had passion for IT and with a bit of 
                 encouragement I finally took up study as a mature age student.<br><br> I have just recently moved back to the South Coast and enjoy the peace and quite
                  the country has to offer. In my spare time I enjoy gardening, growing vegetables and herbs, keeping fit, working on various projects in the shed. I also enjoy photography and reading (sci-fi tragic!).</p>
         </b-col>
     <b-col cols="2"></b-col>     
   </b-row>

  <b-row class="form-group"></b-row>

    <b-row>
      <b-col cols="2"></b-col>
        <b-col cols="8">
          <a class="btn btn-outline-light link-out" href="https://www.instagram.com/jacks_nature_pics/?hl=en" role="button" target="_blank">Instagram Photos</a>
          <a class="btn btn-outline-light link-out" href="https://www.goodreads.com/user/show/86337535-jack" role="button" target="_blank">Goodreads Profile</a>
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
.h1-responsive, 
.h3-responsive {
  text-align: center;
}

.link-out{
  padding: 0.5vw;
  margin: 0.5vw;
  float: right;
}

p2{
    font-family: 'Titillium Web', sans-serif;
    color: lightgray;
    font-weight: 100;
    margin: 0;
}
.p-responsive {
   font-size: calc(50% + 0.4vw + 0.4vh);
}
p {
  margin-bottom: 0;
}
</style>
