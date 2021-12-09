<template>
  <main>
  <div class="container">
    <div class="row row-cols-2 row-cols-lg-5 g-2 g-lg-3">
      <div class="col" v-for="carro in carros" :key="carro.id" >
        <div class="card text-center bg-light">
        <div class="p-3 border bg-light">
          <img :src="carro.imagem" class="card-img-top">
        </div>
        <div class="card-header bg-light">
          <h5 class="text-success"><strong>{{ carro.preco }}</strong></h5>
        </div>
        <div class="card-body">
          <h5 class="card-title">{{ carro.titulo }}</h5>
          <p class="card-text">
            {{ carro.subtitulo}}
          </p>
        </div>
        <div class="card-footer">
          <form class="d-block">
            <button class="btn btn-dark" type="button" onclick="window.location.
            href='./detalhescarro.html'">
              Detalhes
            </button>
          </form>
            <small class="text-success">{{ carro.status }}</small>
        </div>
      </div> <!--card-->
    </div> <!--col-->

    

</div> <!--row-->

<hr class="mt-3">
<div class="row pb-4">
</div>

</div> <!--container-->
</main>
</template>

<script>
export default {
    data() {
        return {
            carros: [
                {
                    id: 1,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 2,
                    imagem: require('@/assets/img/golf-capa.png'),
                    preco: 'R$ 59.900,00',
                    titulo: 'Golf TSI',
                    subtitulo: 'Golf 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 3,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 4,
                    imagem: require('@/assets/img/golf-capa.png'),
                    preco: 'R$ 59.900,00',
                    titulo: 'Golf TSI',
                    subtitulo: 'Golf 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 5,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 6,
                    imagem: require('@/assets/img/golf-capa.png'),
                    preco: 'R$ 59.900,00',
                    titulo: 'Golf TSI',
                    subtitulo: 'Golf 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 7,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 8,
                    imagem: require('@/assets/img/golf-capa.png'),
                    preco: 'R$ 59.900,00',
                    titulo: 'Golf TSI',
                    subtitulo: 'Golf 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                  {
                      id: 9,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 10,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                  {
                      id: 11,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 12,
                    imagem: require('@/assets/img/foto exemplo (1).jpg'),
                    preco: 'R$ 49.900,00',
                    titulo: 'Onix',
                    subtitulo: 'Onix 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                },
                {
                    id: 13,
                    imagem: require('@/assets/img/golf-capa.png'),
                    preco: 'R$ 59.900,00',
                    titulo: 'Golf TSI',
                    subtitulo: 'Golf 2020 completo - Multimidia - Pneus Novos',
                    status: 'Disponível'
                }
            ]
        }
    }
}
</script>

<style>

</style>