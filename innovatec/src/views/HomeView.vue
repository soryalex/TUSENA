<template>
  <div class="home">
    <CarouselComponentVue></CarouselComponentVue>
    <encabezado-logos-component></encabezado-logos-component>
    <encabezado-menu-component></encabezado-menu-component>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import CarouselComponentVue from '@/components/CarouselComponent.vue';
import EncabezadoMenuComponent from '../components/EncabezadoMenuComponent.vue';
import EncabezadoLogosComponent from '../components/EncabezadoLogosComponent.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    CarouselComponentVue,
    EncabezadoMenuComponent,
    EncabezadoLogosComponent
  }
}
</script>
