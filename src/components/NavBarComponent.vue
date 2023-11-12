<template>
    <div class="container">
        <div class="row flex-nowrap ">
            <div class="col-2">
                <img src="" alt="Logo">
            </div>
            <div class="col-10">
                <ul class="nav nav-underline">
                    <li v-for="items in menu" class="nav-item">
                        <a class="nav-link" :class="'active'" aria-current="page" href="#">{{ items.
                        text }}</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'NavBarComponent',
        data(){
            return {
                menu:[
                    {
                        text:'CHARACTERS',
                        active:false,
                    },
                    {
                        text:'COMICS',
                        active:true,
                    },
                    {
                        text:'MOVIES',
                        active:false,
                    },
                    {
                        text:'TV',
                        active:false,
                    },
                    {
                        text:'GAMES',
                        active:false,
                    },
                    {
                        text:'COLLECTIBLES',
                        active:false,
                    },
                    {
                        text:'VIDEOS',
                        active:false,
                    },
                    {
                        text:'FANS',
                        active:false,
                    },
                    {
                        text:'NEWS',
                        active:false,
                    },
                    {
                        text:'SHOP',
                        active:false,
                    },
                ]
            }
        },
        methods:{
            
        }
    }
</script>

<style lang="scss" scoped>

</style>