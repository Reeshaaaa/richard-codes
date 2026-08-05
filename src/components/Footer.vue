<template>
    <footer>
        <p>Richard Fousek 2026</p>
        <p>fousekrichard(at)gmail.com</p>
        <div id="socials">
            <a href="https://github.com/Reeshaaaa" target="_blank" rel="noopener noreferrer">
                <img :src="githubLogo" alt="GitHub" />
            </a>
            <a href="https://www.linkedin.com/in/richard-fousek-090654377/" target="_blank" rel="noopener noreferrer">
                <img :src="linkedinLogo" alt="LinkedIn" />
            </a>
        </div>
    </footer>
</template>

<script setup>
const githubLogo = "https://richard-codes-850027065475-us-east-1-an.s3.us-east-1.amazonaws.com/logo-github.png"
const linkedinLogo = "https://richard-codes-850027065475-us-east-1-an.s3.us-east-1.amazonaws.com/logo-linkedin.png"
</script>

<style scoped>
footer {
    background-color: var(--color-header);
    padding: 20px 0;
}

footer p {
    text-align: center;
    margin: auto;
    color: aliceblue;
}

#socials {
    display: flex;
    justify-content: center;
}

#socials a {
    margin: 3px 7px;
    height: 10px;
    width: 10px;
}
</style>