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
              <p class="p-responsive">
                Currently completing a bachelor of Information Technology with a minor in web design graduating early 2021. Developing skills in full stack development, cloud platforms and strong interest in IOT applications.
             </p>
              </b-col>
          </b-row>


        <b-row>
          <b-col cols="6">
            <h2 class="h2-responsive">Education</h2>
            <p class="p-responsive education-title">Bachelor of Information Technolgy</p>
            <p class="p2-responsive">2018 - 2021</p>
            <p class="p2-responsive">Royal Melbourne Institute of Tehnology</p>
            <p class="p2-responsive">&#8594; Minoring in Web Design</p>
            <p class="p2-responsive">&#8594; Strong focus on programming</p>

            <b-row class="form-group"></b-row>

            <p class="p-responsive education-title">Master of Cloud Computing and Virtualisation</p>
            <p class="p2-responsive">2021 - 2022</p>
            <p class="p2-responsive">Charles Sturt University</p>
            <p class="p2-responsive">&#8594; Cloud Environments</p>
            <p class="p2-responsive">&#8594; Focus on Amazon Web Services</p>

          </b-col>
          <b-col cols="6">
            <h2 class="h2-responsive">Skills</h2>
            <p class="p2-responsive">&#8226; Javascript Libraries (Node.js, Vue.js)</p>
            <p class="p2-responsive">&#8226; Java</p>
            <p class="p2-responsive">&#8226; PostgreSQL</p>
            <p class="p2-responsive">&#8226; HTML, CSS and PHP</p>
            <p class="p2-responsive">&#8226; Wordpress</p>
            <p class="p2-responsive">&#8226; Linux/Unix Environments</p>
            <p class="p2-responsive">&#8226; Agile development metholodgies</p>
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
.education-title {
  color: #35A7FF;
}


</style>