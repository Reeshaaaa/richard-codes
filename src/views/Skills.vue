<template>
    <div id="full-page">
        <Header pageName="Skills" />

        <div id="main-page">
            <Sidebar />

            <div id="main-bar">
                <p>Sample Text</p>
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