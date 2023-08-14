<script setup>
</script>

<template>
    <section class="episodes">
        <div class="label">
            <p class="label__text">Latest episodes</p>
            <button class="button">View all episodes</button>
        </div>
        <div class="episodes-list">
            <article class="episode">
                <img src="/episode-3.png" class="episode__photo">
                <div>
                    <button class="episode__tag">Gear</button>
                    <p class="episode__number">Episode 3</p>
                    <p class="episode__label">Should you get<br>outboard audio gear?</p>
                    <p class="episode__text">Is hardware really worth it when it comes to podcasting? The answer is...it<br>depends. Here’s our reasons on why you might want to consider picking<br>something up.</p>
                    <button class="button">View Episode Details</button>
                </div>
            </article>
            <article class="episode">
                <img src="/episode-2.png" class="episode__photo">
                <div>
                    <button class="episode__tag">Tips & Tricks</button>
                    <p class="episode__number">Episode 2</p>
                    <p class="episode__label">Mic tricks to take<br>you to the next level</p>
                    <p class="episode__text">Stop rolling with those default settings on your mic. These small tweaks will<br>take you from sounding good to great.</p>
                    <button class="button">View Episode Details</button>
                </div>
            </article>
            <article class="episode">
                <img src="/episode-1.png" class="episode__photo">
                <div>
                    <button class="episode__tag">Gear</button>
                    <p class="episode__number">Episode 1</p>
                    <p class="episode__label">The best microphone<br>under $200</p>
                    <p class="episode__text">With so many microphones on the market, how are you supposed to know<br>what’s the best? Take a look at our top picks.</p>
                    <button class="button">View Episode Details</button>
                </div>
            </article>
        </div>
    </section>
</template>

<style scoped lang="sass">
.episodes
    width: 1440px
    display: flex
    padding: 0px 20px
    align-items: center
    margin-top: 100px
    flex-direction: column
    gap: 40px
.label
    min-width: 1400px
    display: flex
    justify-content: space-between
    align-items: center
    &__text
        font-size: 64px
        line-height: 79.2px
        letter-spacing: 2.88px
.episodes-list
    display: flex
    flex-direction: column
    gap: 60px
.episode
    min-width: 1400px
    border-radius: 32px
    background: #000000
    padding: 40px
    display: flex
    gap: 53px
    &__tag
        font-size: 18px
        line-height: 27px
        padding: 3px 16px
        border-radius: 6px
        background-color: #191919
        margin-bottom: 48px
    &__number
        color: #118DA8
        font-size: 17px
        line-height: 27px
        margin-bottom: 18px
    &__label
        font-size: 64px
        line-height: 70.4px
        letter-spacing: 2.56px
        margin-bottom: 28px
    &__text
        color: rgba(255, 255, 255, 0.70)
        font-size: 22px
        line-height: 33px
        margin-bottom: 18px
</style>