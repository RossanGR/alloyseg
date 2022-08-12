<script>
</script>

<template>
    <footer class="footer">
        <div class="container ">
            <div class="footer container-ultrawide">
                <div class="footer__container">
                    <div class="footer__container__img">
                        <a href="index.html"><img class="footer__container__img__logo" src="../assets/logo.svg"
                                alt="logo"></a>
                        <a target="_blank" href="https://alloymit.com/"><img class="footer__container__img__selo"
                                src="../assets/selo-alloypng.png" alt="selo"></a>
                    </div>
                    <ul>
                        <li><a href="#quemsomos">Quem somos</a></li>
                        <li><a href="#seguros">Seguros</a></li>
                        <li><a href="#solucoes">Soluções</a></li>
                        <li><a href="#faq">Faq</a></li>
                        <li><a href="#contato">Contato</a></li>
                    </ul>
                </div>
                <span id="divisor"></span>
                <div class="dados">
                    <div class="dados__endereco">
                        <i class="fa-solid fa-location-dot d-block">
                            <p>ED.ALLOYMIT</p>
                            <p>RUA BARTOLOMEU DE GUSMÃO, 290</p>
                            <p>VILA MARIANA – SP – CEP 04111-020</p>
                        </i>
                    </div>
                    <div id="dados__contact">
                        <i class="fa fa-whatsapp">
                            <a class="white"
                                href="https://api.whatsapp.com/send?phone=5511935030212&text=Seja%20bem-vindo%20a%20AlloySeg!%20Como%20podemos%20ajudá-lo?"
                                target="blank">(11) 93503-0212</a>
                        </i>
                        <p>
                            <i class="fa fa-envelope">
                                <a class="white" href="mailto:sac@alloyseg.com.br">sac@alloyseg.com.br</a>
                            </i>
                        </p>
                        <div class="d-flex center-social">
                            <a class="icon-social" href=" https://www.linkedin.com/company/alloy-seg/" title="Linkedin"
                                target="blank">
                                <i class="fa fa-linkedin-square"></i>
                            </a>

                            <a class="icon-social" href="https://www.instagram.com/alloysegoficial/" title="Instagram">
                                <i class="fa fa-instagram"></i>
                            </a>

                        </div>
                    </div>
                </div>
                <a href="https://api.whatsapp.com/send?phone=5511935030212&text=Seja%20bem-vindo%20a%20AlloySeg!%20Como%20podemos%20ajudá-lo?"
                    style="position:fixed;width:60px;height:60px;bottom:40px;right:40px;background-color:#25d366;color:#FFF;border-radius:50px;text-align:center;font-size:30px;box-shadow: 1px 1px 2px #888;
  z-index:1000;" target="_blank">
                    <i style="margin-top:16px" class="fa fa-whatsapp"></i>
                </a>
                <div class="footer__copyright">
                    <p>© copyright 2022 – AlloySeg. Todos os direitos reservados.</p>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
/* inicio footer*/
a,
p {
    font-style: normal;
}

.dados__endereco i {
    display: flex;
    color: #fdaf41;
}

#dados__contact i {
    display: flex;
    color: #fdaf41;
    margin-bottom: 10px;
}

.footer {
    height: 400px;
    background-color: #1d1d1b;
    display: flex;
    flex-wrap: wrap;
}

.footer__container {
    display: flex;
    width: 80%;
    margin: auto;
    justify-content: space-between;
}

.footer__container ul {
    display: flex;
}

.footer__container__img__logo {
    width: 150px;
}

.footer__container__img__selo {
    width: 130px;
    height: 42px;
    margin: 0 30px;
}

.footer__container ul {
    display: flex;
    flex-wrap: wrap;
}

.footer__container ul li a {
    font-weight: bold;
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
}

.footer__container ul li a:hover {
    border-top: 2px solid var(--green);
    transition: 1s;
}

.dados {
    margin-bottom: 50px;
    display: flex;
    width: 80%;
    margin: 0 auto;
}

#divisor {
    width: 80%;
    display: block;
    margin: 0 auto;
    height: 1px;
    background-color: rgba(204, 204, 204, 0.423);
}

.dados__endereco {
    width: 30%;
}

.dados__endereco p {
    display: block;
    color:
        var(--green);
    font-size: 14px;
    overflow: hidden;
    margin-left: 20px;
    color: #fff;
}

#dados__contact {
    width: 50%;
    margin-left: 30px;
}

#dados__contact a {
    color: var(--green);
    text-decoration: none;
    text-transform: uppercase;
    display: block;
    font-size: 14px;
    margin-left: 8px;
    overflow: hidden;
    font-family: Avenir, Helvetica, Arial, sans-serif;
}

.footer__copyright {
    width: 80%;
    margin: auto;
}

.footer__copyright p {
    color: #87868a;
    font-size: 12px;
    font-weight: bold;
}

.icon-social {
    background: #fdaf41;
    color: #FFF;
    padding: 0px 8px;
    height: auto;
    display: block;
    margin-right: 9px;
    font-size: 19px;
    margin-left: 0px !important;
    transition: .3s;
}

.icon-social i {
    color: #FFF !important;
    font-size: 20px;
    margin-top: 7px;
}

.icon-social:hover {
    background: #fb4b01;
}

footer li {
    list-style: none;
}

.social-img {
    width: 4%;
}

.text-lowercase {
    text-transform: lowercase;
}

.social-text::first-letter {
    text-transform: uppercase;
}

.white {
    color: #fff !important;
    ;
}

@media (max-width: 1024px) {
    #dados__contact {
        margin-left: 0;
    }

    .footer {
        height: unset;
    }

    footer {
        height: 550px;
    }

    .footer__container {
        display: flex;
        flex-wrap: wrap;
        margin: auto;
    }

    .footer__container__img {
        width: 50%;
        margin: 20px auto;
        display: flex;
        flex-wrap: wrap;
    }

    .footer__container__img img {
        margin: 10px auto;
    }

    .footer__container ul {
        width: 100%;
        margin: 10px auto 30px auto;
        display: flex;
        justify-content: center;
    }

    .dados {
        display: flex;
        flex-wrap: wrap;
    }

    .dados__endereco {
        width: 100%;
    }

    .dados__endereco i {
        justify-content: center;
        margin: 30px 0 30px 0;
    }

    #dados__contact {
        width: 100%;
    }

    .dados__endereco p {
        text-align: center;
    }

    #dados__contact i {
        justify-content: center;
        padding: 10px 0;
    }

    .footer__copyright p {
        text-align: center;
        padding: 50px 0 20px 0;
    }

    .center-social {
        justify-content: center;
    }

}

@media (max-width: 480px) {
    .footer__container ul li {
        width: 100%;
        text-align: center;
        margin: 10px 0;
    }

    .center-social {
        justify-content: center;
    }
}

/*fim footer*/
</style>