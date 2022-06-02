<template>
    <section class="content">
        <img
            alt="Vue logo"
            class="content-img"
            src="@/assets/logo.svg"
            width="56 "
            height="56"
        />

        <div class="content-text">
            <h1>Text</h1>
            <span>Content</span>
        </div>
    </section>
</template>

<script setup>

</script>

<style>
    section.content {
        display: flex;
        flex-direction: row;
        margin: 2rem auto;
        text-align: center;
        justify-content: center;
    }

    .content-img {
        width: 50%;
    }

    .content-text {
        display: flex;
        flex-direction: column;
        width: 50%;
        text-align: left;
        border-top: 2px solid var(--color-border);
    }
</style>