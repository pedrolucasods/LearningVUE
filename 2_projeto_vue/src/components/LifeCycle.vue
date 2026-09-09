<template>
    <h1>Meu nome é: {{ nome }} </h1>
</template>

<script>
    export default{
        name:"LifeCycle",
        data(){
            return{
                nome: "Ainda Não sei"
            }
        },
        created(){
            setTimeout(()=>{
                this.nome = "Pedro Lucas"
            },2000)
            
        },
        mounted(){
            setTimeout(()=>{
                this.nome = "Mateus"
            },2000)
        }
    }
</script>