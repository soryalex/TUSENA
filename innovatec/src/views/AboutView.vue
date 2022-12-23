<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import CarouselComponentVue from '@/components/CarouselComponent.vue';
import EncabezadoMenuComponent from '../components/EncabezadoMenuComponent.vue';
import EncabezadoLogosComponent from '../components/EncabezadoLogosComponent.vue';


export default {
    name: 'HomeView',
    components: {
        CarouselComponentVue,
        EncabezadoMenuComponent,
        EncabezadoLogosComponent
    }
}


</script>
