<template>
    <footer class="footer">
        <p>&copy; Web Dev, {{ new Date().getFullYear() }}</p>
        <a href="https://linkedin.com" target="_blank">
            <img src="../assets/images/linkedin-logo.png" alt="linkedin-logo">
        </a>
    </footer>
</template>

<style scoped>

.footer {
    padding: 0 2rem;
    background-color: var(--background-dark);
    display: flex;
    justify-content: space-between;
    align-items: center;
}

p {
    color: var(--text-high-contrast);
}

img {
    height: 3rem;
    padding: 0.5rem;
}



</style>