<template>
    <article class="contact">
      <img src="../assets/contacts/contacts.png" alt="">
      <form action="#">
        <h2>Свяжитесь с нами!</h2>
          <div><label for="text">Ваше имя</label><input type="text" id="text" name="user" placeholder="Турсые Алибекович"></div>
          <div><label for="tel">Контактный телефон</label><input type="tel" id="tel" name="number" placeholder="+7 777 7777 77 77"></div>
          <div><label for="email">Почта</label><input type="email" name="email" id="email" placeholder="info@a-lux.kz"></div>
          <div><label for="message">Сообщение</label><textarea name="text" id="message"></textarea></div>
           
         
          <button type="submit" class="btn">Отправить</button>
      </form>
    </article>
</template>


<script>

 export default {
  name: 'Contacts',
}
</script>



<style scoped>

  


h2 {
  text-align: left;
}
label {
  margin-right: 140px;
  margin-left: 20px;
  text-align: left;
  display: block;
  margin-top: 20px;
}
div {
   margin-top: 10px;
   width: 900px;
   margin-bottom: 60px;
}
form {
  z-index: 5;
  height: 1000px;
  width: 30%;
  padding: 20px;
  background: gray;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
input {
  margin-left: 40px;
  padding: 10px;
  width: 68%;
  height: 50px;
  margin-top: 20px;
}
input::placeholder {
  color: rgba(224, 212, 212, .9);
}
textarea {
  margin-right: 450px;
  height: 150px;
  margin-top: 30px;
  margin-left: 20px;
  resize: none;
  width: 48%;
}
 img {
   width: 100%;
 }
button {
  margin-top: 45px;
  margin-bottom: 180px;
  margin-left: 20px;
  padding-bottom: 20px;
}

</style>
