<script>
</script>

<template>
    <section>
        <div class="container menu__container__h1 col-12">
            <h1 class="display-3">Soluções em Seguros e<br>Benefícios Personalizados</h1>
            <div class="d-flex align-items-center container--btn">
                <b-button class="btn-orcamento" bnt="success" href="#contato">Solicite um orçamento</b-button>
                <a href="#quemsomos" >
                    <p>Confira mais...</p>
                </a>
            </div>
            <img class="menu__container__h1--arrow" src="../assets/arrow-down-sign-to-navigate.svg" alt="seta branca">
        </div>
    </section>
</template>

<style scoped>
.menu__container__h1 {
  margin-top: 200px;
}

.menu__container__h1 h1 {
  color: #fff;
}

.menu__container__h1 a {
  text-decoration: none;
}

.menu__container__h1 a p {
  margin: 0 15px;
  color: #fff;
  text-decoration: none;
}

.btn-orcamento {
  border-radius: 20px;
  padding: 5px 30px;
  background: #16b702;
}

.btn-orcamento:hover {
  background: #17b702a7;
}

.menu__container__h1--arrow {
  width: 25px;
  display: block;
  margin: 144px auto 0px;
  padding-bottom: 20px;
}
@media(max-width:480px){
  .container--btn{
    flex-wrap: wrap;
  }
  .container--btn .btn-orcamento{
    width: 100%;
  }
}
</style>