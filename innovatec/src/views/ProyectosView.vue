<template>
    <div>
        <CarouselComponentVue></CarouselComponentVue>
        <encabezado-logos-component></encabezado-logos-component>
        <encabezado-menu-component></encabezado-menu-component>

        <h1>Proyectos</h1>
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