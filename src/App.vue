<script>
    import Header from "./views/Header.vue";
    import HomeView from "./views/HomeView.vue";
    import OnSaleView from "./views/OnSaleView.vue";
    import NewsView from "./views/NewsView.vue";
    export default(await import('vue')).defineComponent({        
        components: {
            Header,
            HomeView,
            OnSaleView,
            NewsView
        }
    })
</script>

<template>
    <Header />
    <HomeView />
    <OnSaleView />
    <NewsView />
</template>

<style scoped>
</style>
