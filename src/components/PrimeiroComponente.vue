<template>
    
    <h1>Olá Vue!</h1>
    <p> my name is {{ nome }}</p>
    <p>My work is a {{ profissao }}</p>
</template>

<script>


export default {
    name:'PrimeiroComponente',
    data(){
        return{
            nome:"Kauã",
            profissao: "Dev Front end"
        }
    }
}
</script>
