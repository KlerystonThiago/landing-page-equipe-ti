<script>
  import brand from '../assets/images/brand.png'  
  import backheader from '../assets/images/back_header.jpg'  
  export default {
    data() {
      return {
        brand,
        backheader
      }
    }
  }
</script>

<template>
  <div>
    <header>
      <div class="line-contact">
        <div class="container flex justify-content-between">
          <div class="contacts color-grey-4">
            <p>
              <font-awesome-icon class="top-icons" icon="fa-solid fa-phone" /> 3373-2369
            </p>
            <p>
              <font-awesome-icon class="top-icons" icon="fa-solid fa-envelope" /> kleryston@mail.com
            </p>
            <p>
              <font-awesome-icon class="top-icons" icon="fa-solid fa-location-dot" />Rua Mariz de Barro
            </p>
          </div>
          <div class="social-media">
            <font-awesome-icon class="top-icons" :icon="['fab', 'square-facebook']" />
            <font-awesome-icon class="top-icons" :icon="['fab', 'square-twitter']" />
            <font-awesome-icon class="top-icons" :icon="['fab', 'linkedin']" />
            <font-awesome-icon class="top-icons" :icon="['fab', 'square-instagram']" />
          </div>
        </div>
      </div>
      <div class="container flex justify-content-between align-items-center">
        <div class="brand">
          <img :src="brand" alt="">
        </div>
        <nav>
          <ul class="flex menu">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Doctors</a></li>
            <li><a href="#">Contato</a></li>
          </ul>
        </nav>
      </div>
      <div class="container-full background-header" :style="'background-image: url('+backheader+')'">
        <div class="shadow"></div>
        <div class="container-banner flex justify-content-center">
          <div class="container">
            <h1>Kleryston Thiago</h1>
          </div>
        </div>
      </div>
    </header>

    <main>
      
    </main>

    <footer>

    </footer>
  </div>
</template>
