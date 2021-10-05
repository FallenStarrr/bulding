<template>
  <article class="contact">
    <img src="../assets/contacts/contacts.png" alt="builder | строитель" />
    <form action="#">
      <h2>Свяжитесь с нами!</h2>
      <div>
        <label for="text">Ваше имя</label
        ><input
          type="text"
          id="text"
          name="user"
          placeholder="Турсые Алибекович"
        />
      </div>
      <div>
        <label for="tel">Контактный телефон</label
        ><input
          type="tel"
          id="tel"
          name="number"
          placeholder="+7 777 7777 77 77"
        />
      </div>
      <div>
        <label for="email">Почта</label
        ><input
          type="email"
          name="email"
          id="email"
          placeholder="info@a-lux.kz"
        />
      </div>
      <div>
        <label for="message">Сообщение</label
        ><textarea name="text" id="message"></textarea>
      </div>

      <button type="submit" class="btn">Отправить</button>
    </form>
  </article>
</template>

<script>
export default {
  name: "Contacts",
};
</script>

<style scoped>
.contact {
  max-width: 100%;
  position: relative;
}
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
  width: 900px;
}
form {
  z-index: 5;
  max-width: 30%;
  max-height: 100%;
  padding: 20px;
  background: gray;
  display: flex;
  flex-direction: column;
  justify-content: center;
  position: absolute;
  top: 0;
  right: 240px;
}
input {
  padding: 10px;
  width: 20%
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
  max-width: 100%;
}
button {
  margin-top: 45px;
  margin-bottom: 180px;
  margin-left: 20px;
  padding-bottom: 20px;
}
</style>
