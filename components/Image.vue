<template>
    <img class="rounded-xl h-full object-cover w-full transform transition-all ease-in-out duration-150" 
        :src="src" 
        alt="image-portfolio" 
        width="200" 
        height="200">
</template>

<script setup lang="ts">

    defineProps({
        src: String
    })

</script>