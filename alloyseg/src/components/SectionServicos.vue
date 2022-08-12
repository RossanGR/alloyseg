<script>
</script>

<template>
    <div id="solucoes" class="background--orange">
        <section class="container row mx-auto mt-5 align-items-center">
            <h2 class="text-center display-5 title">Soluções</h2>
            <div class="row d-flex align-items-stretch mt-5">
                <div data-circle="" class="col-12 col-sm-12 col-md-12 my-3 col-lg-3 container__servicos circle--before">
                    <h2 class="subtitle text-center h4">Seguros</h2>
                    <p class="text-center">Atuamos com especialistas nos mais diferentes ramos de seguros, e com a
                        parceria
                        de Seguradoras
                        sólidas do mercado, oferecendo assim aos clientes os seguros e benefícios mais modernos e
                        personalizados.</p>
                </div>
                <div data-circle="" class="col-12 col-sm-12 col-md-12 my-3 col-lg-3 container__servicos circle--before">
                    <h2 class="subtitle text-center h4">Benefícios Saúde e odonto</h2>
                    <p class="text-center">Atuamos com empresas especializadas no mercado de benefícios com cobertura
                        nacional e nos diversos segmentos, levando até você diferentes oportunidades.</p>
                </div>
                <div data-circle="" class="col-12 col-sm-12 col-md-12 my-3 col-lg-3 container__servicos circle--before">
                    <h2 class="subtitle text-center h4">Assistências</h2>
                    <p class="text-center">Assistências 24 horas são serviços adicionais que a Alloy Seg disponibilizará
                        no
                        seu seguro, oferecendo comodidade em diversas situações.</p>
                </div>
            </div>
        </section>
    </div>
</template>

<style scoped>
#servicos {
    padding-top: 20px;
}

.background--orange {
    background-image: url(../assets/1_mob.png);
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: contain;
}

section {
    padding-bottom: 300px;
}

.title {
    color: #fb4c05;
    margin-bottom: 50px;
}

.subtitle {
    margin: 100px 0 20px;
}

.arrow {
    display: block;
    margin: auto;
    width: 25px;
    margin-top: 30px;
}

.container__servicos {
    padding: 50px;
    box-shadow: 0px 10px 20px 0px #ddd;
    border-radius: 30px;
    margin: 0 auto;
    background-color: #fff;
    position: relative;
}

.circle--before:before {
    content: "";
    width: 120px;
    height: 120px;
    background-color: #fb4c05;
    position: absolute;
    border-radius: 150px;
    top: 0;
    left: 0;
    z-index: -1;
    margin-top: -60px;
    margin-left: -60px;
}
</style>