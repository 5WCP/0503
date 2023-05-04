<script>
    import OnSaleCard from "../components/OnSaleCard.vue";
    export default {
        components: {
            OnSaleCard
        }
    }
</script>

<template>
    <div class="area2">
        <h2>On Sale</h2>
        <div class="cardArea">
            <OnSaleCard/>
            <OnSaleCard/>
            <OnSaleCard/>
        </div>
    </div>
    <hr>
</template>

<style lang="scss" scoped>
    .area2 {
        margin-top: 32px;

        h2 {
            text-align: center;
        }
        .cardArea {
            display: flex;
            justify-content: space-between;
        }
    }

    hr {
        margin: 32px 0;
    }
</style>