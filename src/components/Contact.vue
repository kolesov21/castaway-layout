<script setup>
</script>

<template>
    <section class="contact">
        <div class="subscribe">
            <p class="subscribe__label">Email Newsletter</p>
            <p class="subscribe__text">Subscribe<br>for updates</p>
        </div>
        <div class="form">
            <div class="input-section">
                <input type="text" class="input" placeholder="Name">
                <input type="text" class="input" placeholder="Email">
            </div>
            <button class="button">Submit</button>
        </div>
        <img src="contact-icon.svg" alt="" class="contact__icon">
    </section>
</template>

<style scoped lang="sass">
.contact
    width: 1400px
    display: flex
    background-color: #000000
    border-radius: 32px
    padding: 60px
    justify-content: space-between
    margin-top: 160px
    position: relative
    &__icon
        position: absolute
        bottom: -30px
        left: -30px
.subscribe
    &__label
        color: #118DA8
        font-size: 18px
        line-height: 27px
    &__text
        font-size: 72px
        line-height: 79.2px
        letter-spacing: 2.88px
.input-section
    display: flex
    flex-direction: column
    gap: 20px
    min-width: 522px
    margin-bottom: 20px
</style>