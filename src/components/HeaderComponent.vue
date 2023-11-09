<template>
    <header>
        <h1>Header</h1>
        <NavBarComponent />
    </header>
</template>

<script>
import NavBarComponent from './NavBarComponent.vue';
    export default {
        name:'HeaderComponent',
        components:{
            NavBarComponent,
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