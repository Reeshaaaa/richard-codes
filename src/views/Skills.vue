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
</template>

<script>
import Header from "../components/Header.vue"
import Sidebar from "../components/Sidebar.vue";
export default {
    name: "App",
    components: {
        Header,
        Sidebar
    }
}
</script>