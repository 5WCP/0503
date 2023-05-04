<script>
</script>

<template>
    <div class="navBar">
        <div class="logo"></div>
        <div class="menuBar"></div>
    </div>
</template>

<style lang="scss" scoped>
.navBar {
    padding: 32px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo {
        width: 2rem;
        height: 2rem;
        background-color: #ac1717;
    }
    .menuBar {
        width: 30px;
        height: 5px;
        background-color: #444;
        border-radius: 15px;
        position: relative;

        &::before , &::after {
            content: "";
            width: 30px;
            height: 5px;
            background-color: #444;
            border-radius: 15px;
            position: absolute;
        }

        &::before {
            top: 10px;
        }

        &::after {
            top: -10px;
        }
    }
}
</style>