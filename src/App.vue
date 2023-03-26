<template>
  <div id="app">
    <div class="infoBox">
        <img src="./assets/logo/vue.png"/>
        <h2 style="color:#333" class="mb-3">tag_transfer</h2>
        <b-button size="sm" class="m-2" style="background-color:#ce2f2f; border:0" href="https://www.npmjs.com/package/tag_transfer">Npm</b-button>
        <b-button size="sm" class="m-2" style="background-color:#333; border:0" href="https://github.com/wendy60113/Transfer_UI">Github</b-button>
    </div>
    <div class="containerBox">
      <div class="uiBox">
        <TransferApp/>
      </div>
  </div>
  </div>
</template>

<script>
import TransferApp from './components/TransferApp.vue'

export default {
  name: 'App',
  components: {
    TransferApp
  }
}
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Alata&display=swap');
body{
  margin: 0;
  padding: 0;
}
#app{
  background-color: #fafafa;
  height: 100vh;
  width: 100vw;

  display: flex;
  flex-wrap: wrap;
  justify-content: center;    
  align-items: center; 
}
.infoBox{
  font-family: 'Alata', sans-serif;
  width: 100%;
  text-align: center;
  img{
    margin: 10px;
    height: 40px;
  }
}
.containerBox{
  width: 100%;
  display: flex;
  justify-content: center;   
}
.uiBox{
  width: 800px;
  height: 400px;
}
</style>
