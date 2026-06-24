<template>
    <header>
        <img :src="imageUrl" alt="S3 image" />
        <div id="header-text">
            <p></p>
            <p></p>
            <h1>Richard Fousek</h1>
            <p>{{ pageName }}</p>
        </div>
    </header>
</template>

<script setup>
const imageUrl = 'https://richard-codes-850027065475-us-east-1-an.s3.us-east-1.amazonaws.com/reesha1080.png'

const { pageName } = defineProps({
    pageName: String
})
</script>
