<template>
    <div id="side-bar">
            <button @click="router.push('/')">Home</button>
            <button @click="router.push('/about')">About Me</button>
            <button @click="router.push('/work_experience')">Work Experience</button>
            <button @click="router.push('/skills')">Skills</button>

    </div>
</template>

<script setup>
import { useRouter } from 'vue-router'
const router = useRouter()
</script>
