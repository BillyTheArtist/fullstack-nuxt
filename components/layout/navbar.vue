<script setup lang="ts">
import BackButton from "/components/elements/BackButton.vue"
import {useState} from "#app"

const user = useState('user')
const setColorTheme = (newTheme: Theme) => {
    useColorMode().preference = newTheme
}

</script>

<template>



</template>