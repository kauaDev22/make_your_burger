<template>
    <Banner/>
    <div class="main-container">
      
        <h1>MONTE SEU HAMBÚRGUER</h1>
        <BurgerForm/>
    </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import BurgerForm from '../components/BurgerForm.vue'

export default{
    name:'Home',
    components:{
        Banner,
        BurgerForm
    }
}


</script>

<style scoped>

.main-container {
    margin: 50px;
    min-height: 250px ;
}

</style>