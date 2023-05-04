<script>
    import Button from "../components/Button.vue";
    export default {
        components: {
            Button
        }
    }
</script>

<template>
    <div class="card2">
        <img src="../assets/Rectangle 6.png" alt="">
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quasi, modi!</p>
        <button class="btn2">push</button>
    </div>
</template>

<style lang="scss" scoped>
    .card2 {
        width: 30%;
        background-color: #fff;
        padding: 0 8px;

        img {
            width: 100%;
        }

        .btn2 {
            padding: 4px 6px;
            margin-left: 40%;
        }
    }
</style>