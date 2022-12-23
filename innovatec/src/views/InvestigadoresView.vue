<template>
    <!-- <header>
        <article>
            <img alt="Vue imagen" src="../assets/sena.png" width="100px" height="100px">
            <h1>Innovatec </h1>
        </article>



    </header> -->

    <div>
        <CarouselComponentVue></CarouselComponentVue>
        <encabezado-logos-component></encabezado-logos-component>
        <encabezado-menu-component></encabezado-menu-component>

        <!-- <h1>Investigadores</h1> -->


        <section>
            <form>
                <fieldset>
                    <legend>Investigadores</legend>
                    <div>
                        <img alt="Vue imagen"
                            src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHw%3D&w=1000&q=80"
                            width="200px" height="200px">
                    </div>
                    <div>
                        <label for="name"> Nombre: Jesus Alberto</label>

                    </div>
                    <hr>
                    <div>
                        <label for="surname"> Apellidos: Ortiz Fuentes</label>

                    </div>
                    <hr>
                    <div>
                        <label for="email"> Correo: fortiz213Qgmail.com</label>

                    </div>
                    <hr>
                    <div>
                        <label for="">Formacion: Ingeniero fisico</label>
                    </div>
                    <hr>
                    <div>
                        <label>Lineas de investigación: Tecnologias de la energia</label>
                    </div>
                    <hr>
                    <div>
                        <label for="">Lineas de investigación: Tecnologias de la energia</label>
                    </div>
                    <hr>
                </fieldset>
            </form>
        </section>
    </div>
</template>
 
<script>
/*// eslint-disable-next-line
// @ is an alias to /src
import inicioCom from '@/components/inicioCom.vue'
 
export default {
 name: 'HomeView',
 components: {
   inicioCom 
 }
}*/


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
 
<style>
header {
    height: 30vh;
    background-color: rgb(255, 252, 250);
}

article {
    display: flex;
    /* border: 1px solid rgb(198, 146, 250); */
    margin: lef;
}

section {
    height: 70vh;
    display: flex;
    justify-content: center;
    background-color: rgb(247, 163, 107);
}
</style> 
 