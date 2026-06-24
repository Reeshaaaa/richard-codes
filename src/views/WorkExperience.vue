<template>
    <div id="full-page">
        <Header pageName="Work Experience" />

        <div id="main-page">
            <Sidebar />

            <div id="main-bar">
                <hr />
                <div class="job-title">
                    <h2>2020 – Road Traffic Survey Worker</h2>
                    <h2>CZ, Louny</h2>
                </div>
                <p>During the pandemic I had a simple part-time job consisting of a few shifts, counting road traffic of up to 1,000 vehicles per hour, from tranquil roads to busy highways. Each shift lasted 4 hours and involved counting cars, bicycles, motorcycles, trucks, and other vehicles. The results were submitted to the Ministry of Transport.</p>
                <hr />

                <div class="job-title">
                    <h2>08/2022 – Hop Picking Machine Worker</h2>
                    <h2>CZ, Ročov</h2>
                </div>
                <p>At the end of summer I spent two weeks straight filling 55 lb hop bags on the most productive hop-picking machine in the area, so we were sometimes in a rush. Shifts lasted twelve hours, excluding meal breaks.</p>
                <hr />

                <div class="job-title">
                    <h2>05/2023 – Stage Manager</h2>
                    <h2>CZ, Louny</h2>
                </div>
                <p>"Hrajeme s Orfem 2023" was a choir competition for children and teens. I set up stage equipment for more than 10 choirs during the event. At the end, we packed and moved the equipment from the venue to a transport vehicle.</p>
                <hr />

                <div class="job-title">
                    <h2>Summer 2024, 2025 – Order Fulfillment Assistant</h2>
                    <h2>CZ, Louny</h2>
                </div>
                <p>I managed processing, fulfillment, and packaging of orders for a stationery store. I worked primarily at the beginning and end of the summer holidays, when the store had the highest volume of orders. I helped implement efficiency improvements in the order workflow.</p>
                <hr />

                <div class="job-title">
                    <h2>2022–2025 – Election Committee Member [6 days]</h2>
                    <h2>CZ, Louny/Postoloprty</h2>
                </div>
                <p>During three election seasons, I assisted with voter registration, ballot distribution, vote counting, and ensuring compliance with election procedures.</p>
                <hr />

                <div class="job-title">
                    <h2>06–09/2026 – Maintenance Worker</h2>
                    <h2>US, Cold Spring</h2>
                </div>
                <p>This was my first job abroad and my first journey overseas. I gained experience as a maintenance worker for Surprise Lake Camp in New York State. It mostly included gardening and maintaining outdoor facilities. I gained cultural experience and improved my English in a professional environment.</p>
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