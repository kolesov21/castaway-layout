<script setup>
</script>

<template>
    <header class="header">
        <div>
            <img src="castaway-logo.svg" alt="Castaway logo">
        </div>
        <div>
            <ul class="header__navigation">
                <li>Home</li>
                <li>Episodes</li>
                <li>About</li>
                <li>Contact</li>
            </ul>
        </div>
    </header>
</template>

<style scoped lang="sass">
.header
    width:  1440px
    display: flex
    justify-content: space-between
    margin: 26px 50px
    align-items: center
    &__navigation
        display: flex   
        column-gap: 40px
        padding: 20px
        justify-content: center
        font-size: 17px
        line-height: 27px
        cursor: pointer
</style>