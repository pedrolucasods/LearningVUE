<template>
    <div>
        <h1>Ola VUE!</h1>
        <p>Meu nome é {{nome}} e trabalho como {{profissao}}</p>
    </div>
</template>

<script>
    export default{
        name: "PrimeiroComponente",
        data(){
            return{
                nome: "Pedro",
                profissao: "Programador"
            }
        }
    }
</script>
