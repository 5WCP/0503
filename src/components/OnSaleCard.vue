<script>
    import Button from "../components/Button.vue";
    export default {
        components: {
            Button
        }
    }
</script>

<template>
    <div class="card">
    <Button />
    </div>
</template>

<style>
    .card {
        width: 30%;
        height: 200px;
        background-image: url(../assets/d1.png);
        background-size: cover;
        background-repeat: no-repeat;
        position: center center;
    }
</style>