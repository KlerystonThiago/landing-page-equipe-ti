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
            <div class="row flex flex-wrap">
              <div class="col-lg-6 flex flex-direction-column justify-content-center tc-white" style="background-color: greens;">
                <h1 class="fs-45 b-margin-2">
                  Cuidados de Saúde Excepcionais para Mulheres
                </h1>
                <p class="t-margin-0">
                  O melhor médico é aquele que mais esperança inspira. A medicina é o remédio para todas as dores humanas, apenas o amor é um mal que não tem cura. O melhor médico é aquele que recebe os que foram desenganados por todos os outros. Medicina é a arte de compartilhar a vida.
                </p>
                <div class="flex t-margin-3">
                  <button class="btn-solid-white r-margin-3">Agendamentos</button>
                  <button class="btn-solid-inline">Saiba Mais</button>
                </div>
              </div>
              <div class="col-lg-6" style="background-color: blues;">
                
              </div>
            </div>
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
