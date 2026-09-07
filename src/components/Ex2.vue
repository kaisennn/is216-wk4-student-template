<script setup>
    import { ref } from 'vue'

    // Add code here
    import wad from '/assets/wad.png'

    const me = ref('/src/assets/me.png') 

    const x = ref(200)
</script>

<template>
    <div id="demo">
        <img v-bind:src="wad"><hr>
        <img v-bind:src="me"><hr>
      
        <img src="../assets/me.png" :width="x">
    </div>
    <!-- Add code here -->
   
</template>
