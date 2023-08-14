<script setup>
</script>

<template>
    <main class="hero">
        <div class="photo">
            <img src="/main-photo.png" alt="Man in headset" class="photo__img">
            <img src="/main-photo-icon.svg" class="photo__icon">
        </div>
        <div class="tagline">
            <div class="tagline__text">
                <p>Take your<br>podcast to the<br><span class="tagline__text_thinner">next</span> <span class="tagline__text_bold">level</span></p>
                <img src="/tagline-text-icon.svg" class="tagline__icon">
            </div>
            <div class="socials">
                <p>Listen on</p>
                <ul class="socials__icons">
                    <li><img src="/socials-green.svg"></li>
                    <li><img src="/socials-red.svg"></li>
                    <li><img src="/socials-orange.svg"></li>
                    <li><img src="/socials-purple.svg"></li>
                    <li><img src="/socials-white.svg"></li>
                </ul>
            </div>
        </div>
    </main>
</template>

<style scoped lang="sass">
.hero
    width: 1440px
    display: flex
    padding: 0px 20px
    align-items: center
    gap: 60px
.photo
    position: relative
    flex-shrink: 0
    &__icon
        position: absolute
        top: -30px
        left: -30px
.tagline
    &__text
        position: relative
        font-size: 70px
        line-height: 88px
        letter-spacing: 3.2px
        &_thinner
            font-size: 75px
        &_bold
            font-size: 80px
            font-weight: 700
    &__icon
        position: absolute
        top: 180px

.socials
    font-size: 15px
    line-height: 24px
    margin: 90px 0px 0px 22px
    &__icons
        margin-top: 16px
        display: flex
        gap: 17px
        flex-shrink: 0
        cursor: pointer
</style>