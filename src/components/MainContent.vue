<template>
    <main>
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
        <section class="section dishes">
            <div class="container">
                <div class="row">
                    <div class="col col-md-12">
                        <h2 class="text-center title">Our Most Popular Dishes</h2>
                    </div>
                </div>
            </div>
        </section>
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
        <div class="parallax"></div>
        <div class="container menu-categories">
            <div class="row section">
                <div class="col col-md-9 col-sm-9 col-xs-12">
                    <h2 class="title">Menu Categories</h2>
                </div>
                <div class="col-md-3 col-sm-3 col-xs-12">
                    <p class="text-right"><a class="btn btn-red" href="#">view the full menu <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a></p>
                </div>
            </div>
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
        <div class="banner_app">
            <div class="container">
                <div class="row">
                    <div class="col col-md-12 col-sm-12 col-xs-12">
                        <p class="occhiello">Download Our</p>
                        <h1><span>Ordering App</span></h1>
                        <p>
                            <img :src="require('@/assets/app-store-badge.png')" alt="">
                            <img :src="require('@/assets/play-store-badge.png')" alt="">
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="container news-section">
            <div class="row section">
                <div class="col col-md-9 col-sm-9 col-xs-12">
                    <h2 class="title">Latest News</h2>
                </div>
                <div class="col-md-3 col-sm-3 col-xs-12">
                    <p class="text-right"><a class="btn btn-red" href="#">read more news <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a></p>
                </div>
            </div>
            <div class="row section pt0 pb24">
                <div class="col col-md-6 col-sm-6 col-xs-12">
                    <div class="card_news">
                        <img :src="require('@/assets/pancake-burger.jpg')">
                        <div class="descrption">
                            <h3>NEW: The Pancake Burger</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi sodales ipsum vel elementum vehicula. Suspendisse sit amet aliquet ex. Pellentesque commodo tortor vel mi</p>
                        </div>
                    </div>
                </div>
                <div class="col col-md-6 col-sm-6 col-xs-12">
                    <div class="card_news">
                        <img :src="require('@/assets/new-milkshake-menu.jpg')">
                        <div class="descrption">
                            <h3>New Milkshake Menu</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi sodales ipsum vel elementum vehicula. Suspendisse sit amet aliquet ex. Pellentesque commodo tortor vel mi</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {
   name: "MainContent",
}
</script>

<style lang="scss">

@import "../styles/app";

/* Focus */
.focus{
    background-color: $white;
    padding: 40px 60px 20px 60px;
    margin-top: -40px;

    ul {
        list-style-type: none;
        display: $d-flex;
        flex-wrap: wrap;
        justify-content: $justify-content-between;
        align-items: $align-items-center;
        text-align: center;
    }

    ul li span {
        text-transform: uppercase;
        padding-left: 15px;
    }
}

/* Box Piatti Popolari */
.card-dishes{

    position: relative;

    .title-dishes {
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
        background-image: url('../assets/skin-on-fries.jpg');
    } 
    .dishes-02{
        background-image: url('../assets/choco-cookie-frappe.jpg');
    }
    .dishes-03{
        background-image: url('../assets/donut-burger.jpg');
    }

}

/* Parallax */
.parallax{
    background-image: url('../assets/parallax.jpg');
    background-size: cover;
    background-position: center center;
    min-height: 600px;
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
        background-image: url('../assets/appetizers.jpg');
    }
    .categories-02{
        background-image: url('../assets/burgers.jpg');
    }
    .categories-03{
        background-image: url('../assets/pizza.jpg');
    }
    .categories-04{
        background-image: url('../assets/patatine.jpg');
    }
    .categories-05{
        background-image: url('../assets/insalata.jpg');
    }
    .categories-06{
        background-image: url('../assets/desserts.jpg');
    }
    .categories-07{
        background-image: url('../assets/beverages.jpg');
    }
    .categories-08{
        background-image: url('../assets/specials.jpg');
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

/* Banner App */
.banner_app{
  background-image: url('../assets/app-ordering-scaled.jpg');
  background-size: cover;
  background-position: center center;
  min-height: 600px;
  display: $d-flex;
  color: $white;

    .occhiello{
      font-size: 40px;
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

    p img{
      padding-right: 30px;
      margin-bottom: 24px;
    }  
}

/* News Section */
.news-section{

  .descrption{
    padding: 30px 25px 25px 25px;
    text-align: center;

    h3{
      font-size:  42px;
      margin-bottom: 5px;
    }

    p{
      font-weight: 200;
      font-size: 18px;
    }

  }

}
</style>