<template>
    <div id="full-page">
        <Header pageName="Home" />

        <div id="main-page">
            <Sidebar />

            <div id="main-bar">
                <h1>Introduction</h1>
                <p>I'm Richard, and I'm an aspiring DevOps engineer. I made this website as a CV for job hunting.</p>

                <h1>About Me</h1>
                <p>In 2023, I graduated from Václav Hlavatý High School in Louny. After that, I studied Japanese philology for three years, which I did not finish. This summer, I spent three months in New York working at a summer camp in a maintenance position. In my free time, I enjoy sim racing, playing bass, playing the game of Go, or making music.</p>
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
