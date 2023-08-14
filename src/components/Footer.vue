<script setup>
</script>

<template>
    <footer class="footer">
        <div>
            <img src="@/assets/castaway-logo.svg" alt="Castaway logo">
            <div class="footer__icons">
                <img src="@/assets/icon-insta.svg">
                <img src="@/assets/icon-facebook.svg">
                <img src="@/assets/icon-twitter.svg">
            </div>
        </div>
        <div class="footer__lists">
            <ul class="list">
                <li>Home</li>
                <li>About</li>
                <li>Episodes</li>
                <li>Contact</li>
            </ul>
            <ul class="list">
                <li>Style Guide</li>
                <li>Instructions</li>
                <li>Changelog</li>
                <li>Credit</li>
                <li>Powered by Webflow</li>
                <li>Licenses</li>
            </ul>
        </div>
        <ul class="footer__socials">
            <li><img src="@/assets/socials-green.svg"></li>
            <li><img src="@/assets/socials-red.svg"></li>
            <li><img src="@/assets/socials-orange.svg"></li>
            <li><img src="@/assets/socials-purple.svg"></li>
            <li><img src="@/assets/socials-white.svg"></li>
        </ul>
    </footer>
</template>

<style scoped lang="sass">
.footer
    width: 1440px
    display: flex
    padding: 0px 20px
    margin: 160px 0px 50px 0px
    justify-content: space-between
    &__icons
        display: flex
        gap: 10px
        margin-top: 20px
    &__lists
        font-size: 17px
        line-height: 27px
        display: flex
        gap: 103px
    &__socials
        display: flex
        gap: 17px

.list
    display: flex
    flex-direction: column
    gap: 10px
</style>