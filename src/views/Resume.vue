<template>
  <div class="resume">
    <b-container>
    <navbar></navbar>

    <b-row>
          <b-col></b-col>
            <b-col cols="10"><h1 class="h1-responsive">Jack Edwards</h1></b-col>
            <b-col></b-col>
         </b-row>
      

          <b-row class="form-group"></b-row>  
          <b-row>
            <b-col cols="3">
              <img src="../assets/dp.png" class="img-fluid" alt="Jack profile picture">
          
            <h2 class="h2-responsive">Education</h2>
            <p class="p-responsive education-title">Bachelor of Information Technolgy</p>
            <p class="p2-responsive">2018 - 2021</p>
            <p class="p2-responsive">Royal Melbourne Institute of Tehnology</p>
            <p class="p2-responsive">&#8594; Minoring in Web Design</p>

            <b-row class="form-group"></b-row>

            <p class="p-responsive education-title">Master of Cloud Computing and Virtualisation</p>
            <p class="p2-responsive">2021 - 2022</p>
            <p class="p2-responsive">Charles Sturt University</p>


              </b-col>
            <b-col cols="8">
              <p class="p-responsive">
               Through my studies I have had exposure to and worked with various programming languages and technologies as briefly outlined below. (TODO)</p>
               <b-row class="form-group"></b-row>
               <p class="p-responsive">I enjoy taking on new challenges and endless learning opportunites IT has to offer. Through my postgrad study in cloud 
                 computing I continue to build on my skills and knowledge.
               </p>
               <b-row class="form-group"></b-row>
              <p class="p-responsive">For an overview of some of the projects I have worked on see the Portfolio section of this site or send me an enquiry via the Contact page (TODO)</p>
              <b-row class="form-group"></b-row>
              <p class="p-responsive">If you would like to see my full work history prior to IT studies see my LinkedIn profile</p>              
              <b-row class="form-group"></b-row>

              <a class="btn btn-outline-light link-out" href="https://au.linkedin.com/in/jse998" role="button" target="_blank">LinkedIn Profile</a>
              
              </b-col>
              

          </b-row>


        <b-row>
          
          
           <!-- <b-col cols="4">
            <h2 class="h2-responsive">Certifications</h2>
            <p class="p-responsive education-title">PlaceHolder AZ101</p>
            <p class="p2-responsive">Issued 2021. Valid until 2024</p>
            <p class="p2-responsive">ABC Tech Corp</p>
          </b-col> -->

          <!-- <b-col cols="4">
            <img src="../assets/Linkedin-Logo.png" class="linkedin" alt="Jack profile picture">
            <div class="container" id="linkedin">
              <p class="p2-responsive">View work history prior to IT.</p>
              <b-row class="form-group"></b-row>
              <a class="btn btn-primary" href="https://au.linkedin.com/in/jse998?trk=profile-badge-cta" role="button">View Profile</a>
            </div>
          </b-col> -->
        
         
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
#linkedin{
  text-align: left;
  border-style:solid;
  border-width: 0px;
  border-color: white;
  padding-left: 0px;
}
.linkedin{
  width: auto;
  height: 20%;
  margin-top: -20px;
}


</style>