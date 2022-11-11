<template>
   
       <div id="main-banner">
        <h1>Make Your Burger</h1>

       </div>
 
</template>

<script>
export default{
    name: "BannerComp"
}

</script>
<style scoped>

#main-banner {
    background-image: url('/public/img/burger.jpg');  
    height: 500px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: flex-start;

   
}
#main-banner h1{
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;

   
}


</style>