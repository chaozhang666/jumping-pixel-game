<template>
  <div class="container">
    <Menu />
    <div class="content">
      <h1>Welcome to The Jumping Pixel Game</h1>
      <br><br><br>
      <h1>Press <code>Space</code> or <code>Enter</code> to Jump.</h1>
      <br><br><br>
      <h1>👈🏻 Let's Start !</h1>
    </div>
  </div>
</template>

<script>
import Menu from '../components/Menu'

export default {
  name: 'Home',
  components: {
    Menu
  }
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
}

.content {
  height: 100vh;
  width: 85vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;  
  background: #c62a88; 
}

code {
  background-color: whitesmoke;
  padding: 10px;
}
</style>