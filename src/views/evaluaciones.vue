<template>
    
    <section class="page-section" >

        <div class="container px-4 px-lg-5">
            <div class="row gx-4 gx-lg-5 justify-content-center ">
                <div class="col-lg-8 col-xl-6 text-center">
                            <h2 class="mt-0">Evaluaciones</h2>
                            <hr class="divider" />
                            <p class="text-muted mb-1">
                            En esta sección pueden encontrarse las calificaciones obtenidas a lo largo de este periodo,
                            tomadas como capturas de la plataforma de educación en línea de la universidad.

                            </p>
 
                    </div>
                </div>

                <p class="text-md-start">
                    <br> 

                    <ul class="text-md-start">
                        <li> <b>Sitio Web de CVs y Asignación</b> </li>
                        <li> <b>Entrega de Repositorio de prácticas GIT</b> </li>
                        <li> <b>Parcial Teórico</b> </li>
                    </ul>
                    <carousel :Slides="imagenes" ></carousel>

                
                    <br>
                    <br>
                    <h4 class="mt-0 text-center" style="background-color: coral; color: aliceblue;">Computo 2</h4>
                    <br>

                    <ul class="text-md-start">
                        <li> <b>Práctica por puntos</b> </li>
                        <li> <b>Laboratorio 1</b> </li>
                        <li> <b>Laboratorio 2</b> </li>
                        <li> <b>Repositorio de prácticas GIT</b></li>
                        <li><b>Parcial computo 2</b></li>
                        <li><b>Portafolio estudiante segundo computo </b> (En proceso de entrega)</li>
                    </ul>
                    <carousel :Slides="imagenes2" ></carousel>

                </p>
                


        </div>


    </section>

</template>

<script>

import carousel from '../components/carousel.vue';


export default({
components:{
carousel,

},
data: () => ({
imagenes: [

    'https://i.imgur.com/Za4DRxy.jpeg',
    'https://i.imgur.com/l9xCyxD.png',
    'https://i.imgur.com/QOPh1Ew.png',
    
],

imagenes2: [
    'https://i.imgur.com/9HFCfpb.png',
    'https://i.imgur.com/UFjtdMp.png',
    'https://i.imgur.com/dw4Mo85.png',
    'https://i.imgur.com/jv3i6ec.png',
    'https://i.imgur.com/9Ib9oHB.png',
    'https://i.imgur.com/E2uTg0f.png', 
    'https://i.imgur.com/gxMusc6.png',
],



})
});


</script>