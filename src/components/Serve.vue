<template>
    <h2>Наши услуги</h2>
     <div class="container"> 
   <div class="goods">
     
       
        <div>

          <img  src="../assets/services/img1.png" alt="">
        <p>Технико-экономическое обоснование</p>

        </div>

        <div>
          <img  src="../assets/services/img2.png" alt="">
        <p>Энергоаудит</p>
        </div>

        <div>
          <img  src="../assets/services/img3.png" alt="">
        <p>Проектирование</p>
        </div>

        <div>
          <img  src="../assets/services/img4.png" alt="">
        <p>Сервисная поддержка</p>
        </div>

        <div>
          <img  src="../assets/services/img5.png" alt="">
        <p>Сертификация</p>
        </div>

        <div>
          <img  src="../assets/services/img6.png" alt="">
        <p>Поставка оборудования
«под ключ»</p>
        </div>

        <div>
          <img  src="../assets/services/img7.png" alt="">
        <p>Сервисная поддержка</p>
        </div>

        <div>
          <img  src="../assets/services/img8.png" alt="">
        <p>Мониторинг оборудования</p>
        </div>

   </div>
   </div> 

   <section id="question">
     
       <h2>Хотите узнать больше?</h2>
      <img src="../assets/questions/Questions.png" alt="">
      <a href="#" class="btn">Связаться</a> 

      <nav>
        <ul class="qnav">
          <li><a href="#">О компании</a></li>
          <li><a href="#">Услуги</a></li>
          <li><a href="#">Контакты</a></li>
          <li><a href="#">Решения</a></li>
          <li><a href="#">Проекты</a></li>
        </ul>
      </nav>
   </section>

</template>

<script>

export default {
  name: 'Serve',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  margin: auto;
  width: 100%;
  max-width: 700px;
}
#question {
  margin-top: 1400px;
  position: relative;
}
a {
  color: white;
}

#question .btn {
  position: absolute;
  bottom: 200px;
}


 .qnav {
    justify-content: center;
    align-items: center;
    color: white;
   display: grid;
   grid-template-columns: repeat(3, 200px);
   grid-row-gap: 10px;
   grid-column-gap: 20px;
  
 }

.btn {
  text-align: center;
 padding-top: 20px;
  display: block;
  background:#62B82D;
  width: 250px;
  height: 60px;
  color: rgb(240, 232, 232)
}

   #question img {
 padding-left: 0;

height: 699px;
width: 100%;
display: block;
background: linear-gradient(179.8deg, #FFFFFF 0.17%, rgba(255, 255, 255, 0) 24.2%),
   }
   
  .goods {
      
      grid-gap: 30px;
      display: grid;
      grid-template-rows: repeat(8, 1fr);
      grid-template-columns: 1fr 1fr;
      justify-content: center;
      align-items: center;    
  }

  .goods img {
      width: 300px;
      height: 200px;
  }

  h2 {
    font-family: Montserrat;
   font-size: 36px;

font-weight: 600;
line-height: 44px;

text-align: left;
    transform: translate(30%, 180px);
    margin-left: 160px;
    margin-bottom: 200px;
  }
 
  p {
    
  font-family: Montserrat;
  font-size: 20px;
  font-weight: 500;
  text-align: center;


  }
  
  

  

</style>
