<template>
  <div id="app">
    <header>
      <!-- NavBar -->
      <nav>
        <div class="container">
          <div class="menu">
            <div class="logo">
              <img :src="require('@/assets/logo.png')" alt="Logo Avadatakeout">
            </div>
            <ul>
              <li><a href="">Home</a></li>
              <li><a href="">Oder Online</a></li>
              <li><a href="">About</a></li>
              <li><a href="">News</a></li>
              <li><a href="">Contact Us</a></li>
            </ul>
          </div>
        </div>
      </nav>
      <!-- Slider -->
      <section class="hero">
        <div class="container">
          <p class="occhiello">Hungry?</p>
          <h1><span>Great Food</span><br>Delivered</h1>
          <p><a class="btn btn-red" href="#">view our menu</a></p>
        </div>
      </section>
    </header>
    <main>
      
    </main>
    <section></section>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style lang="scss">
@import "@/styles/app";

/* Menu */
nav{
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
}
.menu{
  display: $d-flex;
  justify-content: $justify-content-between;
  align-items: $align-items-center;
  padding: 70px 0;

  ul{
    list-style-type: none;
  } 

  ul li{
    display: inline-block;
    padding: 10px 15px;
    font-size: 20px;
  }

  ul li a{
    color: #fff;
    display: block;
    font-weight: 700;
    padding-left:15px;
    padding-right:15px;
  }
}

/* Slider */
.hero{
  background-image: url('./assets/home-hero.jpg');
  background-size: cover;
  background-position: center center;
  padding: 325px 0;
  color: #fff;

  .occhiello{
    font-size: 40px;
    margin-bottom: 12px;
  }

  h1{
    font-size:80px;
    line-height: 1em;
    font-weight: bold;
    font-style: normal;
    margin-bottom: 35px;
  }

  span{
    color: $primary;
  }

}

</style>
