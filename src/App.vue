<template>
  <HeaderComponent />
  <MainContentComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainContentComponent from './components/MainContentComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

  export default {
    name: "App",
    components: {
      HeaderComponent,
      MainContentComponent,
      FooterComponent,
    },
    data() {
        return {

        };
    },
}
</script>

<style lang="scss" scoped>
// Font family
</style>