<script setup>
</script>

<template>
    <section class="about">
        <div class="about-left">
            <p class="about__label">Meet your host</p>
            <p class="about__name">Jacob Paulaner</p>
            <p class="about__text">Jacob has a background in audio engineering, and has<br>been podcasting since the early days.<br><br>He’s here to help you level up your game by sharing<br>everything he’s learned along the way.</p>
        </div>
        <img src="about-photo.png" class="about__photo">
    </section>
</template>

<style scoped lang="sass">
.about
    width: 1440px
    display: flex
    padding: 0px 20px
    align-items: center
    justify-content: space-between
    margin-top: 260px
    &__photo
        flex-shrink: 0
    &__label
        color: #118DA8
        font-size: 18px
        line-height: 27px
    &__name
        font-size: 65px
        line-height: 79.2px
        letter-spacing: 2.88px
        margin-bottom: 28px
    &__text
        color: rgba(255, 255, 255, 0.70)
        font-size: 22px
        line-height: 33px
</style>