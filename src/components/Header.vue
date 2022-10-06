<template>
    <div>
        <div class="row">
            <div class="col-12 col-md-3">
                <h1>Formulario</h1>
                
            </div>
            <div class="col-12 col-md-6">
                <img :src="url" :alt="alt" width="100">


            </div>

        </div>
    </div>
</template>
<script>
    export default {
        data:()=>({
            url:"https://cdn.svgporn.com/logos/nextjs-icon.svg",
            alt:"Vue.js",
            nombre:"",
            edad:0,
            correo:"",

        }),
        methods :{
            addUsser(){
                console.log(this.nombre, this.edad, this.correo);
            },
        },
    };
</script>