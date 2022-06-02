<template>
    <section class="why">
        <h1>Header </h1>
        <span>Subheader</span>
        <div class="card-wrap">
            <Card/>
            <Card/>
            <Card/>
            <Card/>
        </div>
    </section>
</template>

<script setup>
    import Card from "@/components/Card.vue";
</script>

<style>
    section.why {
        display: flex;
        flex-direction: column;
        margin: 2rem auto;
        text-align: center;
    }

    .card-wrap {
        display: flex;
        justify-content: space-between;
    }
</style>