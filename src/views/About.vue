<template>
  <div class="container">
    <Menu />
    <div class="content">
      <h1>About</h1>
    </div>

  </div>
</template>

<script>
import Menu from '../components/Menu'

export default {
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
  display: flex;
  flex-direction: row;
  height: 100vh;
  width: 85vw;
  justify-content: center;
  align-items: center;  
  background: #c62a88; 
}
</style>
