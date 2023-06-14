<template>
    <div>
        <p>Bingo game for {{ game }}</p>
    </div>
</template>

<script setup lang="ts">
    const { game } = useRoute().params;
    
    definePageMeta({
        layout: 'bingo'
    })
</script>

<style scoped>

</style>