<template>
   <header>
     
       <img class="logo" src="../assets/logo.svg" alt="logo">
       <nav>
         <ul class="nav">
           
           <li><a href="#">О компании</a></li>
           <li><a href="#">Услуги</a></li>
           <li><a href="#">Частным домам</a></li>
           <li><a href="#">Для Бизнеса</a></li>
           <li><a href="#">Контакты</a></li>
           
         </ul>
       </nav>
       
      
      
   </header>
  <div class="banner-flex">
   <p>Самые эффективные методы энергосбережения<br>
и накопления</p>
    <img class="banner" src="../assets/banner.svg" alt="">
    </div>

</template>

<script>

export default {
  name: 'Header',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


  .banner {
    width: 100%;
    margin-top: 120px;
  }
  img {
    max-width: 100%;
  }
 .nav {
   margin-left: 298px;
   align-items: center;
   width: 551px;
   list-style: none;
   display: flex;
   justify-content: space-between;
  
 }
 .nav a {
   margin-left: 5px;
   text-decoration: none;
   color: #3A7B12;
 }
  .logo {
    margin-left: 133px;
    width: 126px;
    height: 31px;
  }
  header {
   
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 83px;

    background: #FFFFFF;
  }

  p {
    color: #fff;
    font-family: Montserrat;
    font-size: 36px;
    font-style: normal;
    font-weight: 800;
    text-align: left;

  }

  .banner-flex {
    margin-top: -120px;
    display: flex;
    flex-direction: column;
  }
</style>
