<script setup>
    import { ref } from 'vue'

    // Add code here
    const width = ref("200")
    const height = ref("200")
    const myImg = ref("/assets/me.png")

    const obj = ref({
        width : "200",
        heiht : "200",
        src : "/assets/me.png"
    })
</script>

<template>
    <img v-bind:src="myImg" :width = "width" :height = "height"/>
    <img v-bind="obj"/>
</template>
