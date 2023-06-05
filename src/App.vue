<script setup lang="ts">
</script>

<template>
  <header class="header">
      <span class="logo">mitsram</span>
      <nav class="menu">
        <ul>          
          <li><a href="#">Products</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
      <ul class="profile">
        <li><a class="cart" href="#"><img src="./assets/shopping_cart.svg" alt="cart"><label>(1)</label></a></li>
        <li><a class="account" href="#"><img src="./assets/account_circle.svg" alt="account"></a></li>
      </ul>
  </header>
  
  <main class="content">
    <section class="section">
      <div class="container">
        <div class="search-bar">
          <input type="text" placeholder="Search something...">
          <button type="submit"><img src="./assets/search.svg" alt=""></button>
        </div>
        <h2>Shop Now</h2>        
        <div class="products">
          <div class="product-card">
            <img src="./assets/images/watch.jpeg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="./assets/images/camera.jpeg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="./assets/images/headset.jpeg" alt="Product 3">
            <h3>Product 3</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <button class="btn">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="./assets/images/herbal.jpeg" alt="Product 4">
            <h3>Product 4</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            <button class="btn">Add to Cart</button>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 mitsram. All rights reserved.</p>
    </div>
  </footer>
</template>

<style scoped>

</style>
