<script setup>
import skills from "../data/skills";
import SkillCard from "../components/SkillCard.vue";
</script>


<template>

<div class="container">

    <h1>My Skills</h1>

    <div class="grid">

        <SkillCard
            v-for="skill in skills"
            :key="skill.id"
            :skill="skill"
        />

    </div>

</div>

</template>