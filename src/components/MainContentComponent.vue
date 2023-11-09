<template>
    <main>
        <h2>Main</h2>
        <ContentComponent />
        <BannerComponent />
    </main>
</template>

<script>
import ContentComponent from './ContentComponent.vue';
import BannerComponent from './BannerComponent.vue';
    export default {
        name:'MainContentComponent',
        components:{
            ContentComponent,
            BannerComponent,
        },
        data(){
            return {

            }
        },
    }
</script>

<style lang="scss" scoped>
@use '../assets/partials/variables' as *;

</style>