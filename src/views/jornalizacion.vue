<template>

<section class="page-section" >

    <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5 justify-content-center ">
            <div class="col-lg-8 col-xl-6 text-center">
                        <h2 class="mt-0">Jornalización</h2>
                        <hr class="divider" />
                        <p class="text-muted mb-1">
                        En esta sección puede encontrarse una Jornalización estructurada
                        de todas las temáticas abordadas durante el computo y las actividades
                        realizadas en cada semana como parte del proceso de aprendizaje.
                        </p>
                        <br>
                    </div> 
            
                    <carousel :Slides="imagenes"></carousel>

            </div>
        </div>
</section> 

    
</template>

<script>
    import carousel from '../components/carousel.vue';

    export default ({
        components:{
            carousel,
        },
        data: () => ({
            imagenes: [
                'https://i.imgur.com/0SAuooJ.png',
                'https://i.imgur.com/StnGNxL.png'
            ]
        })
    })

</script>