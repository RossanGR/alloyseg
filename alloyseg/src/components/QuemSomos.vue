<script>

</script>

<template>
    <section id="quemsomos" class="container row mx-auto mt-5 align-items-center">
        <article  class="col-12 col-lg-6">
            <h2 class="display-5">Quem <strong class="font-weight-bold">somos</strong></h2>
            <p>Alloy Seguros Corretora LTDA é uma empresa integradora de soluções para seguros e benefícios, que oferece
                ampla gama produtos e perspectivas inovadoras aos clientes tendo como foco a administração e vendas de
                seguros e Benefícios personalizados.</p>
            <p>Disponibilizamos as melhores condições e produtos personalizados, que potencializam resultados e melhor
                desempenho em diversos segmentos, assegurando qualidade, comprometimento em todas as etapas de
                contratação.</p>
            <p>Nossos departamentos são capacitados proporcionam atendimento técnico, suporte, manutenção e prestação de
                serviços em todo processo de implantação.</p>
            <p>Nossos canais parceiros, estão em constante aperfeiçoamento são especialistas e qualificados, no
                relacionamento com o cliente, avaliam os riscos e disponibilizam as melhores oportunidades de seguros
                durante toda a negociação.</p>
            <img class="arrow" src="../assets/arrow-down-sign-to-navigate-orange.svg" alt="seta laranja">
        </article>
        <aside class="col-12 col-lg-6 img__ilustr" >
            <img class="col-8 ms-auto d-block " src="../assets/img_1.png" alt="imagem ilustrativa">
        </aside>
    </section>
</template>

<style scoped>
#quemsomos{
    padding-top: 50px;
}
h2{
    color: #fb4c05;
    margin-bottom: 50px;
}
.arrow{
    display: block;
    margin: auto;
    width: 25px;
    margin-top: 30px;
}
section{
    position: relative;
}
section:before{
    content: "";
    width: 5px;
    height: 150px;
    background-color:#fb4c05 ;
    position: absolute;
    left: 0;
    bottom: 0;
    transform: translateY(120px);
}
@media(max-width: 991px){
    .img__ilustr{
        margin: 80px auto ;
    }
    .img__ilustr img{
        margin: 0 auto ;
    }
}
</style>