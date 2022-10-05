<template>
  <div class="card">
    <div class="picture-container">
      <img src="./assets/image-equilibrium.jpg" alt="Equilibrium" class="product-picture">
      <div class="overlay">
        <svg class="view-icon" width="48" height="48" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M0 0h48v48H0z"/><path d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z" fill="#FFF" fill-rule="nonzero"/></g></svg>
      </div>
    </div>
    <div class="title">Equilibrium #3429</div>
    <p class="description">Our Equilibrium collection promotes balance and calm.</p>
    <div class="sub-description">
      <div class="cost-container">
        <svg class="eth-icon" width="11" height="18" xmlns="http://www.w3.org/2000/svg"><path d="M11 10.216 5.5 18 0 10.216l5.5 3.263 5.5-3.262ZM5.5 0l5.496 9.169L5.5 12.43 0 9.17 5.5 0Z" fill="#00FFF8"/></svg>
        0.041ETH
      </div>
      <div class="date-container">
        <svg class="date-icon" width="17" height="17" xmlns="http://www.w3.org/2000/svg"><path d="M8.305 2.007a6.667 6.667 0 1 0 0 13.334 6.667 6.667 0 0 0 0-13.334Zm2.667 7.334H8.305a.667.667 0 0 1-.667-.667V6.007a.667.667 0 0 1 1.334 0v2h2a.667.667 0 0 1 0 1.334Z" fill="#8BACD9"/></svg>
        3 days left
      </div>
    </div>
    <div class="credit-container">
      <img src="./assets/image-avatar.png" alt="Jules Wyvern" class="profile">
      Creation of &nbsp;<span class="name">Jules Wyvern</span>
    </div>
  </div>
</template>

<style>

* {
  margin: 0;
  padding: 0;
  list-style: none;
}

#app {
  font-family: Open Sans;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
  width: 100vw;
  background-color: #0c1a2d;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}

.card {
  width: 240px;
  padding: 20px;
  background-color: #15273f;
  border-radius: 12px;
  color: #8ca0bb;
  font-size: 13px;
  line-height: 20px;
  transition: 0.4s;
}

.card:hover {
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 60px;
  transform: scale(1.03)
}

.title {
  transition: 0.4s;
  font-size: 17px;
  margin: 20px 0;
  color: white;
  font-weight: bold;
}

.title:hover {
  color: #33ebef;
  cursor: pointer;
}

.product-picture {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

.picture-container {
  position: relative;
  height: 240px;
}

.overlay {
  position: absolute;
  top: 0px;
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  opacity: 0;
  transition: 0.4s;
  background-color: rgba(0, 251, 255, 0.5);
  border-radius: 12px;
  cursor: pointer;
}

.picture-container:hover .overlay {
  opacity: 1;
}

.description {
  margin-bottom: 20px;
}

.sub-description {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.cost-container {
  color: #33ebef;
  display: flex;
  align-items: center;
  font-weight: bold;
}

.cost-container .eth-icon {
  margin-right: 6px;
}

.date-container {
  display: flex;
  align-items: center;
}

.date-container .date-icon {
  margin-right: 6px;
}

.credit-container {
  padding: 14px 0 6px 0;
  border-top: solid 1px #2f4159;
  display: flex;
  align-items: center;
}

.profile {
  height: 24px;
  margin-right: 10px;
  border: solid 1px white;
  border-radius: 100%;
}

.name {
  color: white;
  transition: 0.4s;
}

.name:hover {
  cursor: pointer;
  color: #33ebef;
}
</style>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>
