<template>
  <div id="app">
    <header>
      <!-- NavBar -->
      <nav>
        <div class="container">
          <div class="row menu">
            <div class="col col-md-4">
              <div class="logo">
                <img :src="require('@/assets/logo.png')" alt="Logo Avadatakeout">
              </div>
            </div>
            <div class="col col-md-8">
              <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Oder Online</a></li>
                <li><a href="">About</a></li>
                <li><a href="">News</a></li>
                <li><a href="">Contact Us</a></li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
      <!-- Slider -->
      <section class="hero">
        <div class="container">
          <div class="row">
            <div class="col col-md-4">
              <p class="occhiello">Hungry?</p>
              <h1><span>Great Food</span><br>Delivered</h1>
              <p><a class="btn btn-red" href="#">view our menu</a></p>
            </div>
          </div>
        </div>
      </section>
    </header>
    <main>
      <!-- Punti di Forza -->
      <div class="container">
        <div class="row">
          <div class="col col-md-12">
            <div class="focus">
              <ul>
                <li>
                  <i class="fa fa-clock-o" aria-hidden="true"></i> <span>24/7 delivery</span>
                </li>
                <li>
                  <i class="fa fa-apple" aria-hidden="true"></i> <span>over 100 dishes</span>
                </li>
                <li>
                  <i class="fa fa-mobile" aria-hidden="true"></i> <span>in app ordering</span>
                </li>
                <li>
                  <i class="fa fa-car" aria-hidden="true"></i> <span>fast delivery</span>
                </li>
              </ul>  
            </div>
          </div>
        </div>
      </div>
      <!-- Titolo Box Piatti Popolari  -->
      <section class="section dishes">
        <div class="container">
          <div class="row">
            <div class="col col-md-12">
              <h2 class="text-center title">Our Most Popular Dishes</h2>
            </div>
          </div>
        </div>
      </section>
      <!-- Box Piatti Popolari  -->
      <div class="container">
        <div class="row">
          <div class="col col-md-4">
            <div class="card-dishes">
              <div class="bkg-dishes dishes-01"></div>
              <h3 class="title-dishes">Skin On Fries</h3>
              <p class="text-center price">$3.00 – $6.00</p>
            </div>
          </div>
          <div class="col col-md-4">
            <div class="card-dishes">
              <div class="bkg-dishes dishes-02"></div>
              <h3 class="title-dishes">Choco Cookie Frappe</h3>
              <p class="text-center price">$4.99</p>
            </div>
          </div>
          <div class="col col-md-4">
            <div class="card-dishes">
              <div class="bkg-dishes dishes-03"></div>
              <h3 class="title-dishes">The Donut Burger</h3>
              <p class="text-center price">$6.99</p>
            </div>
          </div>
        </div>
        <div class="row section pt48">
          <div class="col col-md-12 text-center">
            <p><a class="btn btn-red" href="#">start your order <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a></p>
          </div>
        </div>
      </div>
      <!-- Parallax -->
      <div class="parallax"></div>
      <!-- Menu Categories -->
      <div class="container menu-categories">
        <!-- Title -->
        <div class="row section">
          <div class="col col-md-9 col-sm-9 col-xs-12">
            <h2 class="title">Menu Categories</h2>
          </div>
          <div class="col-md-3 col-sm-3 col-xs-12">
              <p class="text-right"><a class="btn btn-red" href="#">view the full menu <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a></p>
          </div>
        </div>
        <!-- Box -->
        <div class="row section pt0 pb24">
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-01"><span>appetizers</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-02"><span>burgers</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-03"><span>pizzas</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-04"><span>fries</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-05"><span>sides</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-06"><span>desserts</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-07"><span>beverages</span></div>
          </div>
          <div class="col col-md-3 col-sm-6 col-xs-12">
            <div class="bkg-categories categories-08"><span>specials</span></div>
          </div>
        </div>
      </div>
      <!-- Icone -->
      <div class="container">
        <div class="row section row-icon pt0">
          <div class="col-md-3 col-sm-6 col-xs-12 text-center">
            <p><img :src="require('@/assets/ico01.jpg')"></p>
            <p>Vegetarian</p>
          </div>
          <div class="col-md-3 col-sm-6 col-xs-12 text-center">
            <p><img :src="require('@/assets/ico02.jpg')"></p>
            <p>Gluten Free</p>
          </div>
          <div class="col-md-3 col-sm-6 col-xs-12 text-center">
            <p><img :src="require('@/assets/ico03.jpg')"></p>
            <p>Dairy Free</p>
          </div>
          <div class="col-md-3 col-sm-6 col-xs-12 text-center">
            <p><img :src="require('@/assets/ico04.jpg')"></p>
            <p>Keto Friendly</p>
          </div>
        </div>
      </div>     
    </main>
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
  justify-content: $justify-content-between;
  align-items: $align-items-center;
  padding: 70px 0;

  ul{
    list-style-type: none;
    text-align: right;
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

/* Focus */
.focus{
  background-color: $white;
  padding: 40px 60px 20px 60px;
  margin-top: -40px;

  ul{
    list-style-type: none;
    display: $d-flex;
    flex-wrap: wrap;
    justify-content: $justify-content-between;
    align-items: $align-items-center;
    text-align: center;
  }

  ul li span{
    text-transform: uppercase;
    padding-left: 15px;
  }
}

/* Box Piatti Popolari */
.card-dishes{

  position: relative;

  /* &:hover{
    content: "";
    position: absolute;
    background-color: rgba(0,0,0,.3);
    width: 100%;
    top: 0;
    left:0;
  } */

  .title-dishes{
    font-size: 32px;
    text-align: center;
    font-weight: 500;
    margin: 15px 0 3px;

  }

  .price{
    color: $red;
  }

  .bkg-dishes{
    background-size: cover;
    background-position: center center;
    min-height: 480px;  
  }
  .dishes-01{
    background-image: url('./assets/skin-on-fries.jpg');
  } 
  .dishes-02{
    background-image: url('./assets/choco-cookie-frappe.jpg');
  }
  .dishes-03{
    background-image: url('./assets/donut-burger.jpg');
  }

}

/* Parallax */
.parallax{
  background-image: url('./assets/parallax.jpg');
  background-size: cover;
  background-position: center center;
  min-height: 450px;
}

/* Menu Categories */
.menu-categories{

  .bkg-categories{
    background-size: cover;
    background-position: center center;
    min-height: 250px;
    text-transform: uppercase;
    margin-bottom: 24px;
    display: $d-flex;
    justify-content: center;
    align-items: $align-items-center;
    position: relative;
    color: $white;
    font-size: 20px;

    &:after{
      content: "";
      background-color: rgba(0,0,0,.5);
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      width: 100%;
      height: 100%;
    }

    span{
      position: relative;
      z-index: 1;
    }

  }

  .categories-01{
    background-image: url('./assets/appetizers.jpg');
  }
  .categories-02{
    background-image: url('./assets/burgers.jpg');
  }
  .categories-03{
    background-image: url('./assets/pizza.jpg');
  }
  .categories-04{
    background-image: url('./assets/patatine.jpg');
  }
  .categories-05{
    background-image: url('./assets/insalata.jpg');
  }
  .categories-06{
    background-image: url('./assets/desserts.jpg');
  }
  .categories-07{
    background-image: url('./assets/beverages.jpg');
  }
  .categories-08{
    background-image: url('./assets/specials.jpg');
  }
}

/* Icone */
.row-icon{

  p+p{
    font-size: 20px;
    font-weight: bold;
    margin-top:10px;
    margin-bottom: 20px;
  }

}

</style>
