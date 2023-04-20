<template>


    <section class="page-section" >

        <div class="container px-4 px-lg-5">
            <div class="row gx-4 gx-lg-5 justify-content-center ">
                <div class="col-lg-8 col-xl-6 text-center">
                            <h2 class="mt-0">Apuntes</h2>
                            <hr class="divider" />
                            <p class="text-muted mb-1">
                            En esta sección pueden encontrarse los apuntes tomados durante el desarrollo de las
                            clases, tanto prácticas como teóricas que fueron impartidas a lo largo de este computo.
                            </p>
                            <br>
                </div>
                
                <carousel :Slides="imagenes" ></carousel>

                <hr>
                <br>
                <h4 class="mt-0 text-center" style="background-color: coral; color: aliceblue;">Computo 2</h4>
                <br>

                <carousel :Slides="imagenes2" ></carousel>

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

            'https://i.imgur.com/0VYSmfj.png',
            'https://i.imgur.com/vRdwP50.png',
            'https://i.imgur.com/5ZwUs9P.png',
            'https://i.imgur.com/iFWl01r.png',
            'https://i.imgur.com/isn7QZg.png',
            'https://i.imgur.com/o8InTXf.png',
            'https://i.imgur.com/zfDf8lc.png',
            'https://i.imgur.com/qLfs2eO.png',
            'https://i.imgur.com/QP7i6Bp.png',
            'https://i.imgur.com/1fTOUvu.png',
            'https://i.imgur.com/dz3KTTx.png',
            'https://i.imgur.com/lGAG6rS.png',


            
        ],
        imagenes2: [
         'https://i.imgur.com/v0DZgGq.png',
         'https://i.imgur.com/kMV7bF4.png',
         'https://i.imgur.com/jsKgfi5.png',
         'https://i.imgur.com/0cNwLNN.png',
         'https://i.imgur.com/zESP8vz.png',
         'https://i.imgur.com/TGYgzp9.png',
         'https://i.imgur.com/pVEm9uf.png',
         'https://i.imgur.com/xVU9Aaq.png',
         'https://i.imgur.com/yOOme2J.png',
         'https://i.imgur.com/CT67UUz.png',
         'https://i.imgur.com/8CoSLRt.png',
         'https://i.imgur.com/lQWVqmn.png',
         'https://i.imgur.com/bovOY8I.png',
         'https://i.imgur.com/s81TkKP.png',
         'https://i.imgur.com/6WStLmh.png',
         'https://i.imgur.com/RQO9s5m.png',
         'https://i.imgur.com/EHBlW3Q.png',
        ],


    })

}); 


</script>
  