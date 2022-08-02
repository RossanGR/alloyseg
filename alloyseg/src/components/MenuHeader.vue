<template>
  <div>
    <div class="container container__header">
      <b-navbar type="dark" class="nav__container" toggleable="lg">
        <b-navbar-brand href="#"><img src="@/assets/media/logo.svg"></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <!-- Right aligned nav items -->
        <b-collapse id="nav-collapse" class="justify-content-end" is-nav Right>
          <b-navbar-nav>
            <b-nav-item class="mx-3 nav__item" ref="#">Quem somos</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#">Seguros</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#">Benefícios</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#">Blog</b-nav-item>
            <b-nav-item class="mx-3 nav__item" href="#">Contato</b-nav-item>
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
  border: 1px solid red;
  border-radius: 25px;
  padding: 0 15px;
}

.nav__item a {
  color: #fff;
  padding: 3px;
}

</style>
