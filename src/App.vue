<script>
import Modal from './components/Modal.vue'
export default{
  name: 'App',
  components: {Modal},
  data(){
    return {
      title : 'My First Vue App :)',
      header:'Sign up for the giveaway',
      text:'Grab your ninja swag for half price !'
    }
  },
  methods: {
 
  }
}
</script>

<template>


  <main>
    <h1>{{title }}</h1>
   <Modal :header="header" :text="text"/>
  </main>
</template>


<style>
body{
  background: white;
}
#app{
  font-family: Avenir, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 60px;
}

h1{
  display: inline-block;
}


</style>
