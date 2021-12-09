<template>
  <div class="home">
     <carousel-home />

<br>
    <h2 class="text-center fw-bold">ESTOQUE</h2>
<br>

<listar-carros />

<div style="height: 128px;" class="d-block d-md-none"></div>
<div style="height: 153px;" class="d-none d-md-block d-lg-none"></div>
<div style="height: 129px;" class="d-none d-lg-block"></div>

  </div>
</template>

<script>
// @ is an alias to /src
import CarouselHome from '@/components/home/CarouselHome'
import ListarCarros from '../components/home/ListarCarros.vue'
export default {
  name: 'Home',
  components: { CarouselHome, ListarCarros, }

}
</script>
