<template>
    <ul id="navigation">
            <nav class="navbar">
                <router-link to="/"><li>Home</li></router-link>
                <router-link to="resume"><li>Qualifications</li></router-link>
                <router-link to="portfolio"><li>Portfolio</li></router-link>
                <router-link to="about"><li>About</li></router-link>
                <router-link to="contact"><li>Contact</li></router-link>
            </nav>
        </ul>
</template>


<script>
export default {
}
</script>

<style scoped>


ul {
    position: relative;
    display: block;
}

li {
    display: inline;
    text-align: center;
    padding-right: 0vw;
    text-decoration: none; 
    font-family: 'Titillium Web', sans-serif; 
    font-weight: 900;
    letter-spacing: 4px;
    color: #DA4167;
    font-size: calc(50% + 0.5vw + 0.5vh);
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
.router-link-exact-active > li{
  opacity: 1;
  text-decoration: none;
  color: #91CFFF;
  text-shadow: 0px 0px 30px #B6DF5D;
  /* OG shadow and text colour: #35A7FF  */
}

a, a:link, a:visited, a:focus, a:hover, a:active{
  text-decoration:none !important;
}


</style>