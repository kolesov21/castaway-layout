<script setup>
</script>

<template>
    <section class="reviews">
        <div class="review">
            <div class="review__rating">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
            </div>
            <p class="review__text">I can’t recommend this podcast enough</p>
            <p class="review__author">Betty Lacey</p>
        </div>
        <div class="review">
            <div class="review__rating">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
            </div>
            <p class="review__text">Jacob is the best in the business</p>
            <p class="review__author">Adam Driver</p>
        </div>
        <div class="review">
            <div class="review__rating">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
            </div>
            <p class="review__text">A wealth of audio knowledge</p>
            <p class="review__author">Marcus Brown</p>
        </div>
        <div class="review">
            <div class="review__rating">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
            </div>
            <p class="review__text">Every episode is a gem!</p>
            <p class="review__author">Jessica Knowl</p>
        </div>
        <div class="review">
            <div class="review__rating">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
            </div>
            <p class="review__text">Whoa whoa, let me take some notes!</p>
            <p class="review__author">Scott Adams</p>
        </div>
        <div class="review">
            <div class="review__rating">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
                <img src="review-icon.svg">
            </div>
            <p class="review__text">I’ve upped my game considerably since I started listening</p>
            <p class="review__author">Steven Blast</p>
        </div>
    </section>
</template>

<style scoped lang="sass">
.reviews
    width: 1440px
    display: flex
    padding: 0px 20px
    margin-top: 160px
    flex-wrap: wrap
    gap: 16px
.review
    width: 456px
    height: 346px
    flex-shrink: 0
    border-radius: 32px
    background: #000
    padding: 50px
    &__rating
        display: flex
        gap: 5px
        margin-bottom: 21px
    &__text
        font-size: 36px
        line-height: 43.2px
        margin-bottom: 19px
    &__author
        color: rgba(255, 255, 255, 0.70)
        font-size: 24px
        line-height: 28.8px
</style>