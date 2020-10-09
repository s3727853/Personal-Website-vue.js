<template>

    <ul id="navigation">
            <nav class="navbar">
                <router-link to="/"><li>Home</li></router-link>
                <router-link to="resume"><li>Resume</li></router-link>
                <router-link to="portfolio"><li>Portfolio</li></router-link>
                <router-link to="about"><li>About</li></router-link>
                <router-link to="contact"><li>Contact</li></router-link>
            </nav>
        </ul>
    
</template>


<script>
export default {
    
}
//console.log(this.$router.currentRoute);
</script>

<style scoped>

</style>