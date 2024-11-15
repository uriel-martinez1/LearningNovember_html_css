<template>
    <header class="site-header">
        <div class="site-logo">
            <img src="../assets/images/site-logo.png" />
        </div>
        <nav id="header-nav">
            <router-link class="links" v-bind:to="{ name: 'home' }">Home</router-link>
            <router-link class="links" v-bind:to="{ name: 'about' }">About Us</router-link>
        </nav>
    </header>
</template>

<style scoped>
.site-header {
    padding: 0 2rem;
    background-color: var(--background-dark);
    display: flex;
    justify-content: space-between;
    align-items: center;  
    height: 4rem;  
}

a {
    font-family: var(--ff-heading);
    color: white;
    text-decoration: none;
}

a:hover, 
a:focus-visible {
    cursor: pointer;
    color: var(--clr-ghost);
}

.links {
    margin-left: 1rem;
}


.site-logo {
    height: 3rem;
}

.site-logo img {
    height: 100%;
    width: auto;
}

</style>