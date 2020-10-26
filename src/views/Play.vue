<template>
  <div class="container">
    <Menu />
    <div class="content">
      <canvas id="myCanvas"></canvas>
    </div>

  </div>
</template>

<script>
import Menu from '../components/Menu'
export default {
  name: 'Play',
  data() {
    return {
      birdX: 200,
      birdY: 200,
      birdSize: 200
    }
  },
  methods: {
    // drawBird() {
    //   ctx.beginPath();
    //   ctx.rect(birdX, canvas.height - birdSize - birdY, birdSize, birdSize);
    //   ctx.fillStyle = "yellow";
    //   ctx.fill();
    //   ctx.closePath();
    // }
  },
  mounted() {
    var canvas = document.getElementById("myCanvas");
    var ctx = canvas.getContext("2d");
    ctx.beginPath();
    ctx.rect(this.birdX, 2000 - this.birdSize - this.birdY, this.birdSize, this.birdSize);
    ctx.fillStyle = "red";
    ctx.fill();
    ctx.closePath();

  },
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

canvas {
  width: 100%;
  height: 100%;
  background-color: yellow;
}
</style>