<template>
  <div id="app">
    <div class="testOut">
    <TransferApp/>
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
<style>
body{
  margin: 0;
  padding: 0;
}
#app{
  background-color: #fafafa;
  height: 100vh;
  width: 100vw;

  display: flex;
  justify-content: center;    
  align-items: center; 
}
.testOut{
  width: 700px;
  height: 400px;
}
</style>
