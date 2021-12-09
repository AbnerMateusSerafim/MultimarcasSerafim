<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <b-img src="@/assets/img/logo.png" width="100px" />
      </a>
      <button class="navbar-toggler ml-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" data-target="#nav2">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active text-white" aria-current="page" href="./Página Inicial.html"><strong>Início</strong></a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="Contato.html">Contato</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="endereco.html">Endereço</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="login.html">Entrar</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Buscar..." aria-label="Search">
          <button class="btn btn-outline-dark btn-warning" type="submit">Buscar</button>
        </form>
      </div>
    </div>
  </nav>
        <router-view/>

  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
