<template>
    <section class="hero">
        <div class="hero-text">
            <h1>Heading</h1>
            <span>subheading</span>
        </div>
        <div class="hero-img">
            <img src="" alt="">
        </div>
    </section>
</template>

<style>
section.hero {
        position: relative;
        display: flex;
        height: 600px;
    }

    section.hero > .hero-text {
        flex: 0 0 auto;
        width: 50%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        margin: 1rem ;
        justify-content: center;
    }
    
    section.hero > .hero-text h1 {
        position: relative;
        display: inline;
    }

    section.hero > .hero-img {
        flex: 0 0 auto;
        width: 50%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        margin: 1rem ;
        justify-content: center;
    }

</style>