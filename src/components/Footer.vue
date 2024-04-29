<template>
  <div id="page-container">
   <div id="content-wrap">
     <!-- o resto do conteúdo da página -->
   </div>
   <footer id="footer"> <p>Make Your Burger &copy; 2024</p></footer>
 </div>
  
</template>

<script>
export default {
    name:'Footer',
}
</script>


<style scoped>
#page-container {
  position: relative;
  min-height: 100vh;
}

#content-wrap {
  padding-bottom: 2.5rem;    /* altura do rodapé */
}
    #footer {
      height: 500px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #fcba03;
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    bottom: 0;
    width: 100%;
}

</style>