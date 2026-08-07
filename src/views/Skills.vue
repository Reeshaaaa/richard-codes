<template>
    <div id="full-page">
        <Header pageName="Skills" />

        <div id="main-page">
            <Sidebar />

            <div id="main-bar">
                <hr />
                <h1>Languages</h1>
                <p><b>Czech</b> – My native language.</p>
                <p><b>English (B2/C1)</b> – I learned English mostly online by immersion since I was a kid. School helped me structuralize it. Spending 3 months in USA helped me improve it. In 2023, I recieved a CEFR B2 certificate.</p>
                <p><b>Japanese (N4)</b> – Lower intermediate after 4 semesters of learning it in college.</p>
                
                <hr />
                <h1>Software Development Life-cycle</h1>
                <p><b>SDLC</b> means <b>Plan – Write – Build – Test – Deploy</b> the software application. This web application deployed on cloud is the proof.</p>
                <p>Here is my core knowledge list of relevant tools/languages for the SDLC:</p>
                <ul>
                    <li>HTML, CSS, JavaScript</li>
                    <li>VueJS</li>
                    <li>Node.js</li>
                    <li>MongoDB</li>
                    <li>Jest</li>
                    <li>Linux, AWS</li>
                    <li>Git</li>
                    <li>AI use for coding</li>
                </ul>
                <p>You can view my projects including this website on my <a href="https://github.com/Reeshaaaa" target="_blank" rel="noopener noreferrer">Github</a> page.</p>
            </div>
        </div>
    </div>
    <Footer />
</template>

<script>
import Header from "../components/Header.vue"
import Sidebar from "../components/Sidebar.vue"
import Footer from "../components/Footer.vue"

export default {
    name: "App",
    components: {
        Header,
        Sidebar,
        Footer
    }
}
</script>

<style scoped>
h1 {
    margin: 1rem 0 0.25rem;
}

p, ul {
    margin: 0.25rem;
}
</style>