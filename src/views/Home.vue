<template>
  
    <div class="home">
        <b-container>
         
         <b-row>
           <b-col></b-col>
            <b-col cols="10"><h1 class="h1-responsive">Hi,</h1></b-col>
            <b-col></b-col>
         </b-row>
         <b-row>
           <b-col></b-col>
            <b-col cols="10"><h1 v-lettering class="firstLine">I'm Jack Edwards,</h1></b-col>
            <b-col></b-col>
         </b-row>
         <b-row>
           <b-col></b-col>
            <b-col cols="10"><h1 v-lettering class="secondLine">IT student graduating in 2021.</h1></b-col>
            <b-col></b-col>
          </b-row>
          <b-row class="form-group"></b-row>
          <b-row>
            <b-col></b-col>
           <b-col cols="10"> <h2 class="h2-responsive">Developing skills in full stack web development, cloud platforms, Java programming and creating IOT projects in my spare time.</h2></b-col>
          <b-col></b-col>
          </b-row>

          <b-row>
            <b-col></b-col>
           <b-col cols="10">
             <ul id="navigation">
                <router-link to="resume"><li class="menu-text">Resume</li></router-link>
                <router-link to="portfolio"><li class="menu-text">Portfolio</li></router-link>
                <router-link to="about"><li class="menu-text">About</li></router-link>
                <router-link to="contact"><li class="menu-text">Contact</li></router-link>
            </ul>
            </b-col>
          <b-col></b-col>
          </b-row>
  
        </b-container>
    </div>
        
</template>

 

<script>
// import Navbar from '@/components/Navbar.vue';

export default {
  name: 'Home',
  // components: { "navbar": Navbar}
}


</script>

<style>
 .home {
   padding-top: 20vh;
 }
 @media only screen and (max-width: 1100px) {
   .home {
     padding-top: 5px;
   }
 }
/*Fonts*/
h1 {
    font-family: 'Titillium Web', sans-serif;
    color: white;
    letter-spacing: 1px;
}
h2{
    font-family: 'Titillium Web', sans-serif;
    color: lightgray;
}
h3{
    font-family: 'Titillium Web', sans-serif;
    color: lightgray;
    font-weight: 100;
}

.h1-responsive,
.firstLine,
.secondLine {
  font-size: calc(70% + 1vw + 1vh);
}
.h2-responsive {
  font-size: calc(50% + 0.7vw + 0.7vh);
}
.h3-responsive {
  font-size: calc(20% + 0.7vw + 0.7vh);
}
.menu-text {
  font-size: calc(30% + 0.6vw + 0.6vh)
}

/*Individual lettering colours, using v-lettering*/

 .firstLine .vl--i-5, .firstLine .vl--i-10{ 
    color: red;
}
 .secondLine .vl--i-1, .secondLine .vl--i-2{ 
    color: red;
}



/* ul {
    position: relative;
    display: block;
} */

li {
    /* display: inline;
    text-align: center;
    padding-right: 2vw; */
    text-decoration: none; 
    font-family: 'Titillium Web', sans-serif; 
    font-weight: 900;
    letter-spacing: 4px;
    /* font-size: 19px; */
    color: #DA4167;
    
    -moz-transition: all 0.2s ease-in;
    -o-transition: all 0.2s ease-in;
    -webkit-transition: all 0.2s ease-in;
    transition: all 0.2s ease-in;
}

li:hover,
#active-page {
    cursor: pointer;
    color: #35A7FF;
    text-shadow:0px 0px 30px #35A7FF;
    -moz-transition: all 0.2s ease-in;
    -o-transition: all 0.2s ease-in;
    -webkit-transition: all 0.2s ease-in;
    transition: all 0.2s ease-in;
}
.router-link-active,
.router-link-exact-active {
  text-decoration: none;
  color: #000;
}

a, a:link, a:visited, a:focus, a:hover, a:active{
  text-decoration:none !important;
}

</style>