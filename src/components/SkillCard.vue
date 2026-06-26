<script setup>
defineProps({
    skill: Object
})
</script>

<template>

    <div class="skill-card">

        <h2>{{ skill.name }}</h2>

        <p>{{ skill.category }}</p>

        <p>{{ skill.level }}</p>

    </div>

</template>

<style scoped>

.skill-card{
    border:1px solid #ddd;
    padding:20px;
    border-radius:10px;
}

</style>