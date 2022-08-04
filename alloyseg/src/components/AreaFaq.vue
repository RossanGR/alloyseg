<script>

</script>

<template>
    <div id="faq" class="background--orange">
        <section class="container">
            <h2 class="display-5 text-center">FAQ</h2>
            <div class="accordion" role="tablist">
                <b-card no-body class=" container--accordion">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button class="mt-1" block v-b-toggle.accordion-1 variant="info">É possível escolher qualquer seguro e
                            benéfico, de acordo com meu interesse?</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-1"  accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text class="text-center text--white">Disponibilizamos as melhores condições e
                                produtos personalizados. Dessa forma, você escolhe seus seguros e benefícios.
                            </b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>

                <b-card no-body class=" container--accordion">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button class="mt-1" block v-b-toggle.accordion-2 variant="info">Qualquer empresa pode contratar a
                            AlloySeg?</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text class="text-center text--white">A AlloySeg foi planejada para segurar empresas
                                de pequeno, médio e grande porte que estejam em atividade.</b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>

                <b-card no-body class=" container--accordion">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button class="mt-1" block v-b-toggle.accordion-3 variant="info">O que é Seguro Garantia?</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                            <b-card-text class="text-center text--white">É a opção de caução mais segura e completa para
                                as suas obrigações contratuais - Oferece proteção contra eventuais prejuízos decorrentes
                                do não cumprimento das especificações de um contrato.</b-card-text>
                        </b-card-body>
                    </b-collapse>
                </b-card>
            </div>
        </section>
    </div>
</template>

<style scoped>
.accordion {
    margin: 0;
    padding-bottom: 100px;
}

.background--orange {
    background-color: #ff4c00;
}

h2 {
    padding: 30px 0;
    color: #fff;
}

.container--accordion {
    background-color: #ff4c00;
    box-shadow: 0 0 4px 0 #fff;
    border: none;
    border-radius: 25px;
    margin: 20px 0 0 0;
}
.container--accordion p{
    margin: 0;
}

button {
    width: 100%;
    background-color: unset;
    color: #fff;
    border: none;
}

button:focus-within,
button:focus-visible,
button:focus,
button:active,
button:active:focus {
    background-color: unset;
    border: none;
    box-shadow: none;
    outline: none;
    color: #fff;
}

button:hover {
    width: 100%;
    background-color: unset;
    color: #fff;
}

header {
    border-bottom: unset;
}

.text--white {
    color: #fff;
    border-top: 1px solid rgb(255 255 255 / 41%);
    padding: 15px 0 0 0;
}
.mt-1{
    font-weight: bold;
}
</style>