<template>
    <div id="full-page">
        <Header pageName="About Me" />

        <div id="main-page">
            <Sidebar />

            <div id="main-bar">
                <h1>About Me</h1>
                <p>I was born on July 1st 2003 in my current hometown, Louny, Czechia. From 2010 to 2019, I attended Prokop Holý Elementary School. During that period, I tried various activities such as soccer, karate, golf, baseball, and speedcubing. In karate, I earned a gold medal and three bronze medals, and in speedcubing, I received a silver medal. As for speedcubing, you can find my results <a href="https://www.worldcubeassociation.org/persons/2018FOUS02">here.</a></p>
                <p>In 2019, I started studying at Václav Hlavatý High School. During this time, I began some of my current hobbies (bass guitar, the game of Go, etc.). In IT class during Python lectures, I discovered my talent, which eventually led me to develop skills in the field and build this website.</p>
                <p>At that time, I was also a part-time commentator for F1 game leagues, providing commentary for the <a href="https://www.youtube.com/watch?v=3sbA0OXTQvA&t=5113s">Czech Racing League</a> and <a href="https://www.youtube.com/watch?v=9mwybcRFC-o&t=1s">FrontRunner Racing</a>. This helped me overcome my biggest weakness — communication skills — by streaming for up to 50 viewers. It was a great opportunity to improve my verbal communication and vocabulary.</p>
                <p>After graduating from high school, I started studying Japanese philology at Palacký University Olomouc (2023–2026). Despite three years of dedication, I realized I didn't see a reason to further develop those skills, so I quit without graduating. Instead, I saw my future elsewhere. In winter 2026, I took part in the IT Fundamentals course by <a href="https://www.techworld-with-nana.com/">Techworld With Nana.</a></p>
                <p>So what came next? I decided to work in New York from June to September 2026 at a summer camp as maintenance staff. Since September, I have been looking for a job.</p>
                <p>My current hobbies are playing bass guitar and occasionally making music in FL Studio. I also play the game of Go, an ancient Chinese board game of placing stones on intersections. According to the <a href="https://europeangodatabase.eu/EGD/Player_Card.php?&key=19725684">European Go Database</a>, I have reached the rating of 4-kyu.</p>
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