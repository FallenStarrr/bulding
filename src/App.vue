<template>
  <Header/>
  <Serve/>
  <House/>
 <Business/>
 <Contacts/> 
</template>

<script>
import Header from './components/Header.vue'
import Serve from './components/Serve.vue'
 import House from './components/House.vue'
import Business from './components/Business.vue'
import Contacts from './components/Contacts.vue'

export default {
  name: 'App',
  components: {
    Header,
    Serve,
     Business,
     House,
    Contacts
  }
}
</script>

<style>
.btn {
  margin-top: 80px;
  text-align: center;
 padding-top: 20px;
  display: block;
  background:#62B82D;
  width: 250px;
  height: 60px;
  color: rgb(240, 232, 232);
}
* {
  overflow-x: hidden;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  list-style: none;
}



a {
  text-decoration: none;
}
img {
  max-width: 100%;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
