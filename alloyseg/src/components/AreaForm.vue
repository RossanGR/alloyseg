<script>
</script>

<template>
    <div id="contato" class="background--orange pb-5">
        <section class="container row mx-auto align-items-center">
            <article class="col-12 col-lg-6">
                <h2 class="display-5 text-center mb-1">Bem-vindo à Alloyseg!</h2>
                <p class="text-white text-center">Entre em contato conosco:</p>
                <div class="row">
                    <a style="color: #fff;" class="text-center mt-3 mb-2" href="mailto:sac@alloyseg.com.br">alessandro.pereira@alloyseg.com.br</a>
                    <a style="color: #fff;" class="text-center pb-5" href="tel:11975536929">(11) 97553-6929</a>
                </div>
            </article>
            <aside class="col-12 col-lg-6">
                <!-- Formulário -->
                <form id="llCaptureForm" class="llformCustom"
                    style="background-color: rgba(255, 255, 255, 1) !important;" action="//paginas.rocks/capture"
                    method="post">
                    <input type="hidden" id="mid" name="mid" value="656718" />
                    <input type="hidden" id="fid" name="fid" value="52438" />
                    <input type="hidden" id="formType" name="formType" value="dynamic" />
                    <div>
                        <label for="llfield69862">Nome</label>
                        <input type="text" id="llfield69862" name="llfield69862" placeholder="Digite seu nome"
                            data-required="true" required />
                        <div class="field-error" id="llerror69862"></div>
                    </div>
                    <div>
                        <label for="llfield69863">E-mail</label>
                        <input type="email" id="llfield69863" name="llfield69863" placeholder="Digite seu e-mail"
                            data-required="true" required />
                        <div class="field-error" id="llerror69863"></div>
                    </div>
                    <div>
                        <label for="llfield69864">Celular</label>
                        <input type="tel" id="llfield69864" name="llfield69864" placeholder="Digite DDD + Seu Número"
                            data-required="true" required />
                        <div class="field-error" id="llerror69864"></div>
                    </div>
                    <div>
                        <label for="llfield78545">Mensagem</label>
                        <textarea id="llfield78545" name="llfield78545" placeholder="Digite sua mensagem"></textarea>
                        <div class="field-error" id="llerror78545"></div>
                    </div>
                    <div>
                        <div class="field-error" id="LGPDValidation"></div>
                        <div class="checkbox-list" data-required="true">
                            <div class="checkbox">
                                <label>
                                    <input type="checkbox" id="LGPDValidation" name="LGPDValidation"
                                        style="-webkit-appearance: auto !important;" value="1" />Autorizo a AlloySeg a
                                    usar meus dados para, exclusivamente, entrar em contato comigo para oferecer seus
                                    serviços.
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="button-bar">
                        <button style="background-color: #16b702 !important; width: 90%;" type="submit">Enviar</button>
                    </div>
                    <div class="loading-box">
                        <img src="//paginas.rocks/content/images/spinner.gif" />
                        <div>loading...</div>
                    </div>
                    <div class="error-box">
                        <img src="//paginas.rocks/content/images/error-icon.png" />
                        <div></div>
                        <button type="button" class="btn" id="btn-error">Ok</button>
                    </div>
                    <img src="https://llimages.com/redirect/redirect.aspx?A=V&f=52438&m=656718"
                        style="display: none;" />
                </form>
            </aside>
        </section>
    </div>
</template>

<style scoped>
#contato {
    padding-top: 30px;
}

.background--orange {
    background-color: #ff4c00;
}

h2 {
    color: #fff;
}

p,
h2 {
    margin: 0;
}
form{
    border-radius: 10px;
}
</style>