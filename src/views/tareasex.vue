<template>
    
    <section class="page-section" >

        <div class="container px-4 px-lg-5">
            <div class="row gx-4 gx-lg-5 justify-content-center ">
                <div class="col-lg-8 col-xl-6 text-center">
                            <h2 class="mt-0">Tareas Ex-aula</h2>
                            <hr class="divider" />
                            <p class="text-muted mb-1">
                            En esta sección puede encontrarse una pequeña descripción de las
                            tareas ex-aula realizadas hasta el momento.
                            </p>
                </div>

     
            </div>

            <dl><dt>Sitio web y asignación en parejas</dt><dd>
                    Esta tarea consistió en crear un sitio web que contuviera los Curriculums Vitae de los
                    integrantes del grupo de trabajo, al mismo tiempo a cada grupo se les asignó un ejercicio
                    en especifico el cual debían de desarrollar.

                    <br><br>

                    Posteriormente a esto, se subió el repositorio de trabajo a github y luego se hizo el deploy de 
                    este haciendo uso de GitHub Pages, el enlace obtenido se envió en un buzón de entrega. <br>
                    Despues de la entrega, la clase teórica se realizo la exposición del sitio web y asignación 
                    ante el resto de la clase y la Ingeniera encargadad de la Asignatura.



                </dd></dl>

            <br>
            <hr>
            
            <carousel :Slides="imagenes"></carousel>

            <br>
                <h4 class="mt-0 text-center" style="background-color: coral; color: aliceblue;">Computo 2</h4>
            <br>

            <dl><dt>Tarea Semana 10</dt><dd>
                    Esta tarea consistió en apartir de un esquema crear las clases necesarias,
                    diferenciando entre clases abstractas e interfaces según sea necesario.

                    <br><br>

                    Para la realización de esta tarea tambien se tomó en cuenta si era necesario
                    implementar una interfaz, o heredar de una clase abstracta.

            </dd></dl>

            <carousel :Slides="imagenes2"></carousel>

            
            <dl><dt>Laboratorio #2</dt><dd>
                Esta actividad no fue una tarea como tal, pero consistio en un labotorio 
                que desarrollamos en parejas, y que nofe realizado durante la hora de clases

                <br><br>
                Esta actividad consistió en, apartir de un esquema crear las clases o interfaces
                según lo pidiera el esquema y crear objetos según las clases creadas con sus propios métodos
                para ser mostrados posteriormente en una tabla.

            </dd></dl>

            <carousel :Slides="imagenes3"></carousel>


            

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

    'https://i.imgur.com/Q2XGuOD.jpeg',
    'https://i.imgur.com/yDiTFBq.png',
    'https://i.imgur.com/RaOWti2.png',
    'https://i.imgur.com/FRzk2ZU.jpeg',
    'https://i.imgur.com/CUjX6kX.jpeg',

    
],

imagenes2: [
    'https://i.imgur.com/22DMakd.png',
    'https://i.imgur.com/Yb4DO9g.png',
    'https://i.imgur.com/qeDV474.png',
    'https://i.imgur.com/XLncyN2.png',

],

imagenes3: [
    'https://i.imgur.com/6o7hYLZ.png',
    'https://i.imgur.com/7EkHxuk.png',
    
],



})
});


</script>