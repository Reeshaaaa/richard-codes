<template>
    <header>
        <img :src="imageUrl" alt="S3 image" class="profile-image" />
        <div id="header-text">
            <p></p>
            <p></p>
            <div class="title-row">
                <h1>Richard Fousek</h1>
            </div>
            <p>{{ pageName }}</p>
        </div>
        <div id="icon" @click="toggleTheme">
            <img :src="themeIcon" alt="Light and dark mode icon" class="theme-icon" />
        </div>
    </header>
</template>

<script setup>
const themeIcon = 'https://richard-codes-850027065475-us-east-1-an.s3.us-east-1.amazonaws.com/theme-toggle.svg'
const imageUrl = 'https://richard-codes-850027065475-us-east-1-an.s3.us-east-1.amazonaws.com/reesha1080.png'

const { pageName } = defineProps({
    pageName: String
})

const toggleTheme = () => {
    const root = document.documentElement

    if (root.classList.contains('dark')) {
        root.classList.remove('dark')
    } else {
        root.classList.add('dark')
    }
}
</script>
