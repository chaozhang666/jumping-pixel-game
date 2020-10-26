<template>
  <div>
    <div class="menu animate__animated animate__slideInDown">
      <router-link to="/">
        <h1>Moving <br/> Pixel Block</h1>
      </router-link>
      <div class="nav">
        <router-link to="/">
          <button>home</button>
        </router-link>
        <router-link to="/play">
          <button>play</button>
        </router-link>
        <router-link to="/shop">
          <button>shop</button>
        </router-link>
        <router-link to="/about">
          <button>about</button>
        </router-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.menu {
  height: 100vh;
  width: 15vw;
  background-color: #590995;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.menu h1 {
  text-align: center;
  color: whitesmoke;
  text-shadow: 1px 2px 3px white;
  padding: 10px;
  margin-bottom: 50px;
  text-decoration: none;
}

.nav {
  display: flex;
  flex-direction: column;
}

.nav button {
  background-color: black;
  text-align: center;
  border: 0px;
  width: 120px;
  color: white;
  text-align: center;
  margin: 30px;
  padding: 15px 20px; 
  font-size: 20px;
  text-transform: uppercase;
}

.nav button:hover {
  background-color: white;
  color: black;
  cursor: pointer;
  transition: 0.8s;
}

</style>