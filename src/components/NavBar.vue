<template>
  <div class="main-container">
    <nav class="nav-wrapper">
      <div class="store-name">
        Obinna's Store
      </div>
      <div>
        <ul>
          <li>Shop</li>
          <li>My Cart</li>
          <li>Placeholder</li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-container{
  width: 100%;
  height: 64px;
  background-color: #ee6e73;
  color: white;
}

.nav-wrapper{
  display: flex;
  align-items: center;
  justify-content: space-around;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline;
  margin: 0 10px;
}

.store-name{
  font-size: 2.1rem;
}
</style>
