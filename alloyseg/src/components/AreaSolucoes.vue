<script>

</script>

<template>
    <section id="seguros" class="container row mx-auto mt-5 align-items-center">
        <article class="col-12 col-lg-6">
            <img class="col-8 mr-auto d-block img__ilustr" src="@/assets/media/img_2.png" alt="imagem ilustrativa">
        </article>
        <aside class="col-12 col-lg-6">
            <p class="h3 subtitulo">Áreas de soluções</p>
            <h2 class="display-5">Seguros e assistências <strong class="font-weight-bold">diversificadas</strong></h2>
            <p>Atuamos com especialistas nos mais diferentes ramos de seguros, e com a parceria de Seguradoras sólidas
                do mercado, oferecendo assim aos clientes os seguros e benefícios mais modernos e personalizados:</p>
            <div class="row mt-5 justify-content-md-center px-3">
                <ul class="col-12 col-md-8 col-lg-4">
                    <li>Seguro Garantia</li>
                    <li>Responsabilidade Civil</li>
                    <li>Rural</li>
                    <li>Cyber</li>
                    <li>D&O</li>
                </ul>
                <ul class="col-12 col-md-8 col-lg-4">
                    <li>Patrimoniais</li>
                    <li>Equipamentos Portáteis</li>
                    <li>Aluguel</li>
                    <li>Previdência Privado</li>
                    <li>Transportes</li>
                    <li>Convenção Coletiva</li>
                </ul>
                <ul class="col-12 col-md-8 col-lg-4">
                    <li>Saúde e Odontológico</li>
                    <li>Ambiental</li>
                    <li>RC Geral</li>
                    <li>Riscos de Engenharia</li>
                </ul>
            </div>
        </aside>
    </section>
</template>

<style scoped>
h2 {
    color: #fb4c05;
    margin-bottom: 50px;
}

.subtitulo {
    color: #b0b0b0;
}

.arrow {
    display: block;
    margin: auto;
    width: 25px;
    margin-top: 30px;
}

@media(max-width: 991px) {
    .img__ilustr {
        margin: 0 auto;
    }

    section {
        display: flex;
        flex-direction: column-reverse;
    }

    article {
        margin: 100px 0;
    }

}
</style>