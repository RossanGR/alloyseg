<template>
  <div>
    <div class="container container__header">
      <b-navbar type="dark" class="nav__container" toggleable="lg">
        <b-navbar-brand href="index.html"><img src="../assets/logo.svg"></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <!-- Right aligned nav items -->
        <b-collapse id="nav-collapse" class="justify-content-end" is-nav Right>
          <b-navbar-nav>
            <b-nav-item class="mx-3 nav__item" href="#quemsomos">Quem somos</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#seguros">Seguros</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#solucoes">Soluções</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#faq">FAQ</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#contato">Contato</b-nav-item>
          </b-navbar-nav>

        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container__header {
  padding: 30px 20px;
  display: flex;
  justify-content: space-between;
}

img {
  width: 200px;
}

.nav__container {
  width: 100%;
}

.nav__item:last-child {
  border: 1px solid #ff4c00;
  border-radius: 25px;
  padding: 0 15px;
  transition: .3s;
}

.nav__item:last-child:hover{
  background: #ff4c00;
}

.nav__item a {
  color: #fff;
  padding: 3px;
}

@media(max-width: 991px) {
  .nav__item:first-child {
    padding-top: 20px;
  }

  .nav__item:last-child {
    border: none;
    padding: 10px 0;
  }

  .nav__item {
    padding: 10px 0;
  }
}
</style>
