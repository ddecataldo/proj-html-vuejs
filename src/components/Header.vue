<template>
    <!-- NavBar -->
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
                <li
                    v-for="(item, i) in menuItems" 
                    :key="i"
                >
                    <a :class="item.active === true ? 'active' : ''" :href="item.src" :alt="item.alt">{{ item.name }}</a>

                </li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
      <!-- Slider -->
      <section class="hero">
        <div class="container">
          <div class="row">
            <div class="col col-md-6">
              <p class="occhiello">Hungry?</p>
              <h1><span>Great Food</span><br>Delivered</h1>
              <p><a class="btn btn-red" href="#">view our menu</a></p>
            </div>
          </div>
        </div>
      </section>
    </header>
</template>

<script>
export default {
    name: "Header",
    data(){
        return{
            menuItems: [
                {
                    src: "#",
                    name: "Home",
                    active: true,
                },
                {
                    src: "#",
                    name: "Oder Online",
                    active: false,
                },
                {
                    src: "#",
                    name: "About",
                    active: false,
                },
                {
                    src: "#",
                    name: "News",
                    active: false,
                },
                {
                    src: "#",
                    name: "Contact Us",
                    active: false,
                },
            ]
        };
    },
}
</script>

<style lang="scss">

@import "../styles/app";

/* Menu */
nav{
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
}
.menu{
  justify-content: space-between;
  align-items: center;
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

  ul li a.active{
    color: #fcdc31;
  }
}

/* Slider */
.hero{
  background-image: url('../assets/home-hero.jpg');
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
    color: #fcdc31;
  }
}

</style>