<script>
    import NewsCard from "../components/NewsCard.vue";
    import Button from "../components/Button.vue";
    export default {
        components: {
            NewsCard,
            Button
        }
    }
</script>

<template>
    <div class="area3">
        <h2>News</h2>
        <div class="cardArea">
            <NewsCard v-for="item in [1,2,3]" />
        </div>
        <Button />
    </div>
</template>

<style lang="scss" scoped>
    .area3 {
        .cardArea {
            display: flex;
            justify-content: space-between;
        }

        h2 {
            text-align: center;
        }
    }
</style>