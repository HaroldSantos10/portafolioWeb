<template>
    
    <section class="page-section" >

        <div class="container px-4 px-lg-5">
            <div class="row gx-4 gx-lg-5 justify-content-center ">
                <div class="col-lg-8 col-xl-6 text-center">
                            <h2 class="mt-0">Prácticas</h2>
                            <hr class="divider" />
                            <p class="text-muted mb-1">
                            En esta sección pueden encontrarse las prácticas que fueron realizadas a lo largo de este computo
                            se incluye una pequeña explicación de forma general de estas.

                            </p>
                        
                
                </div>

            <br>
                <h5>Práctica #1</h5>
                <p class="text-md-start">
                    <br>

                    En esta primera práctica se estudiaro las nociones básicas de Javascript, entre las temáticas
                    se pueden mencionar:
                    
                    <br>
                    <br>
                    <ul class="text-md-start">
                        <li>Tipos de datos soportados por JavaScript</li>
                        <li>Caracteríscticas del código escrito en JavaScript</li>
                        <li>Tipos de sintaxis de funciones dentro de JavaScript</li>
                        <li>Algunos métodos de JavaScript</li>
                    </ul>
                    
                </p>
                <carousel :Slides="imagenes" ></carousel>

                <hr>
                <br>
                <br>
                <h5>Práctica #2</h5>
                <p class="text-md-start">
                    <br>
                    En esta primera práctica se comenzó a integrar código Html con un script de JavaScript
                    para darle ciertas funcionalidades adicionales con las cuales ser capaces de darle mayor
                    dinamismo a los componentes. 
                    <br>

                    Al mismo tiempo se comenzó a utilizar Javascript para "escuchar" y manipular eventos dentro 
                    del DOM.
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes2" ></carousel>

                <hr>
                <br>
                <br>
                <h5>Práctica #3</h5>
                <p class="text-md-start">
                    <br>

                    En esta primera práctica se comenzó a Trabajar con VueJS, estableciendo los primeros conceptos básicos del 
                    funcionamiento, la instalación de Vue, la instalación del Vue CLI, los diferentes tipos de proyectos que 
                    se pueden crear haciendo uso de Vue y la diferencia en su estructura..
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes3" ></carousel>

                <hr>
                <br>
                <br>
                <h5>Práctica #4</h5>
                <p class="text-md-start">
                    <br>

                    En esta primera práctica se trabajó mas ampliamente con vue, en este caso utilizando vipe para 
                    mostrar una forma más rápida de levantar un proyecto, se comenzó a consumir el API Countries 
                    para mostrar de que forma vue puede trabajar los datos dinámicamente mediante las directivas.
                    <br>

                    Al mismo tiempo se comenzó a utilizar el módulo 'vue-route' configurado de manera manual para controlar
                    las rutas de como se deben mostrar las vistas dentro de la página web, ya que se agregó una nueva vista 
                    que consiste en un filtro de donde se dividen los datos del API según su región.
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes4" ></carousel>

                <hr>
                <br>
                <br>
                <h5>Práctica #5</h5>
                <p class="text-md-start">
                    <br>

                    En esta primera práctica se terminó de cosumir la API countries, en esta caso el filtro ya 
                    fue capaz de mostrar los paises que forman parte de cada continente en la vista ordenados.
                    Para hacer mas ordenado el proceso de visualización se tomó a bien la utilización de un 
                    paginador llamado vue-paginate el cual mediante la directiva v:for fue capaz de ordenar los datos.
                    <br>

                    Tambien se incluyo bootstrap en el proyecto, como una forma de darle un estilo más apropiado y llamativo.
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes5" ></carousel>
                <br>
                <br>

                <div class="text-center">
                    <br>

                    <a href="https://github.com/HaroldSantos10/Programacion_IV_2023.git" target="_blank" rel="noopener noreferrer">
                        <i class="fab fa-github fa-lg">Enlace al repositorio computo 1</i>
                    </a>
                    
                </div>
                

                <hr>
                <br>
                <h4 class="mt-0 text-center" style="background-color: coral; color: aliceblue;">Computo 2</h4>
                <br>
                <h5>Práctica #7</h5>
                <p class="text-md-start">
                    <br>

                    Introducción al uso de php, conociendo la sintaxis del lenguaje mediante la 
                    utilización de un ejercicio en el cual se tienen dos oraciones en diferentes lenguajes
                    y cambiar el idioma según la elección.

                    <br>
                    <br>

                    
                </p>

                <carousel :Slides="imagenes7" ></carousel>



                <hr>
                <br>
                <br>
                <h5>Práctica #8</h5>
                <p class="text-md-start">
                    <br>
                    Se crea un ejemplo de un php usando un formulario para crear, editar, eliminar registros
                    de nombres de persoans y mostrarlos en una lista.
                    
                    <br>

                    Los datos son guardados como array en un archivo .txt llamado Datos.
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes8" ></carousel>


                <hr>
                <br>
                <br>
                <h5>Práctica #9</h5>
                <p class="text-md-start">
                    <br>

                     Desarrollo de una practica para conocer los pilares fundamentales de la programación 
                     orienteda a objetos en la cual se utilizaron diferentes conceptos, como propiedades, métodos,
                     modificadores de acceso entre otros. 
                    <br>
                    En esta practica en concreto se busco la abstracción de las entidades Mascota y Libro,
                    para obtener la represetanción de estas usando el paradigma POO.
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes9" ></carousel>


                <hr>
                <br>
                <br>
                <h5>Práctica #10</h5>
                <p class="text-md-start">
                    <br>

                    En esta semana se estudiaron los conceptos, principios, caracteristicas y 
                    demás consideraciones que se deben tener al momento de trabajar con clases 
                    abstractas y con interfaces.
                    <br>
                    Es importante reconocer la forma como deben de emplearse estos 2 tipos de entidades
                    y cuando es importante utilizarlas, para esta semana se encargó una tarea adicional
                    que puede ser encontrada en el apartado de tareas ex-aula.
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes10" ></carousel>

                <hr>
                <br>
                <br>
                <h5>Práctica #11</h5>
                <p class="text-md-start">
                    <br>

                    Creación del primer proyecto con Laravel, archivos que se deben descargar para usar composer
                    que comandos se deben ejecutar en la terminal y cuales son los posibles errores y como solucionarlos.
                    <br>

                    Esta semana tambien se realizó la conexión a una base de datos MySql, al mismo tiempo realizando las
                    migraciones para que se guarden en la base de datos conectada
                    
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes11" ></carousel>

                <hr>
                <br>
                <br>
                <h5>Práctica #12</h5>
                <p class="text-md-start">
                    <br>
                    En esta practica semanal, se realizo un crud usando el framework de Laravel que 
                    permitió entender de mejor manera la integración de las diferentes partes que componen 
                    la estructura MVC con la cual esta creada el proyecto de Laravel.
                    
                    <br>
                    Tambien se aprendieron los diferentes comandos que se deben ejecutar para la creación
                    automática de modelos, controles, formas de crear views y como se deben integrar dentro
                    de las rutas.
                                       
                    <br>
                    <br>

                    
                </p>
                <carousel :Slides="imagenes12" ></carousel>

                <div class="text-center">
                    <br>

                    <a href="https://github.com/HaroldSantos10/Computo2_ProgramacionIV.git" target="_blank" rel="noopener noreferrer">
                        <i class="fab fa-github fa-lg">Enlace al repositorio computo 2</i>
                    </a>
                    
                </div>

            </div>
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

    'https://i.imgur.com/dNNJcs9.png',
    'https://i.imgur.com/FS3bNBA.png',
    'https://i.imgur.com/gVodz1F.png',
    
],
imagenes2: [

    'https://i.imgur.com/ONrfgJR.png',
    'https://i.imgur.com/6QdVQIg.png',
    'https://i.imgur.com/JkBhhm6.png',
    
],
imagenes3: [

    'https://i.imgur.com/NwgfAfu.png',
    'https://i.imgur.com/jBL04BK.png',
    'https://i.imgur.com/bUHw789.png',

],

imagenes4: [

    'https://i.imgur.com/ZeryFE2.png',
    'https://i.imgur.com/T3mJc4u.png',
    'https://i.imgur.com/yOQhEvD.png',
    'https://i.imgur.com/KvCi9XS.png',
    'https://i.imgur.com/xdyq3OA.png',
    'https://i.imgur.com/G2wg3VH.png',
    
],
imagenes5: [
    'https://i.imgur.com/l5ZnTSE.png',
    'https://i.imgur.com/2CPyeEi.png',
    'https://i.imgur.com/h9oEn7I.png',    
    'https://i.imgur.com/YejTi5a.png',
    'https://i.imgur.com/iaT14ne.png',
    'https://i.imgur.com/yMgM1HE.png', 
],

imagenes7:[
    'https://i.imgur.com/F4Ry7KH.png',
    'https://i.imgur.com/48lEhxt.png',
],
imagenes8:[
    'https://i.imgur.com/ZLqQPWc.png',
    'https://i.imgur.com/Re6VLiI.png',
],
imagenes9:[
    'https://i.imgur.com/7kkSmIC.png',
    'https://i.imgur.com/HNKd5GC.png',
    'https://i.imgur.com/yDLupkX.png',
],
imagenes10:[
    'https://i.imgur.com/AnZx8Ib.png',
    'https://i.imgur.com/fZikEXp.png',
    'https://i.imgur.com/HerlmN6.png',
],
imagenes11:[
    'https://i.imgur.com/QzMKe5m.png',
    'https://i.imgur.com/kgWdfak.png',
],
imagenes12:[
    'https://i.imgur.com/Rk2ES5d.png',
    'https://i.imgur.com/ArYsyLi.png',
],


})
});


</script>