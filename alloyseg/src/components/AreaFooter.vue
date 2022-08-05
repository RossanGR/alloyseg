<script>
</script>

<template>
        <footer class="footer">
          <div class="container ">
            <div class="footer container-ultrawide">
              <div class="footer__container">
                  <div class="footer__container__img">
                      <a href="index.html"><img class="footer__container__img__logo" src="../assets/logo.svg" alt="logo"></a>
                      <a target="_blank" href="https://alloymit.com/"><img class="footer__container__img__selo" src="../assets/selo-alloypng.png" alt="selo"></a>
                  </div>
                  <ul>
                      <li><a href="#quemsomos">Quem somos</a></li>
                      <li><a href="#seguros">Seguros</a></li>
                      <li><a href="#servicos">Serviços</a></li>
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
                      <i class="fa-solid fa-phone-flip">
                         <a style="color: #fff;" href="tel:11975536929">(11) 97553-6929</a> 
                      </i>
                      <i class="fas fa-envelope">
                          <a style="color: #fff;" href="mailto:sac@alloyseg.com.br">alessandro.pereira@alloyseg.com.br</a>
                      </i>
                  </div>
              </div>
              <div class="footer__copyright">
                  <p>© copyright 2022 – AlloySeg. Todos os direitos reservados.</p>
              </div>
          </div>
          </div>
      </footer>
</template>

<style scoped>
/* inicio footer*/
a,p{
    font-style: normal;
}
.dados__endereco i{
    display: flex;
    color: #fdaf41;
}
#dados__contact i{
    display: flex;
    color: #fdaf41;
    margin-bottom: 10px;
}
.footer{
    height: 400px;
    background-color: #1d1d1b;
    display: flex;
    flex-wrap: wrap;
}
.footer__container{
    display: flex;
    width: 80%;
    margin: auto;
    justify-content: space-between;
}
.footer__container ul{
    display: flex;
}
.footer__container__img__logo{
    width: 150px;
}
.footer__container__img__selo{
    width: 130px;
    height: 42px;
    margin: 0 30px;
}
.footer__container ul{
    display: flex;
    flex-wrap: wrap;
}
.footer__container ul li a{
    font-weight: bold;
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
}
.footer__container ul li a:hover{
    border-top: 2px solid var(--green);
    transition: 1s;
}
.dados{
    margin-bottom: 50px;
    display: flex;
    width: 80%;
    margin: 0 auto;
}
#divisor{
    width: 80%;
    display: block;
    margin: 0 auto;
    height: 1px;
    background-color: rgba(204, 204, 204, 0.423);
}
.dados__endereco{
    width: 30%;
}
.dados__endereco p{
    display: block;
    color:
    var(--green);
    font-size: 14px;
    overflow: hidden;
    margin-left: 20px;
    color: #fff;
}
#dados__contact{
    width: 50%;
    margin-left: 30px;
}
#dados__contact a{
    color:var(--green);
    text-decoration: none;
    text-transform: uppercase;
    display: block;
    font-size: 14px;
    margin-left: 20px;
    overflow: hidden;
}
.footer__copyright{
    width: 80%;
    margin: auto;
}
.footer__copyright p{
    color: #87868a;
    font-size: 12px;
    font-weight: bold;
}
footer li{
    list-style: none;
}
@media (max-width: 1024px){
    #dados__contact {
        margin-left: 0;
    }
    .footer {
        height: unset;
    }
    footer{
        height: 550px;
    }
    .footer__container{
        display: flex;
        flex-wrap: wrap;
        margin: auto;
    }
    .footer__container__img{
        width: 50%;
        margin: 20px auto;
        display: flex;
        flex-wrap: wrap;
    }
    .footer__container__img img{
        margin: 10px auto;
    }
    .footer__container ul{
        width: 100%;
        margin: 10px auto 30px auto;
        display: flex;
        justify-content: center;
    }
    .dados{
        display: flex;
        flex-wrap: wrap;
    }
    .dados__endereco{
        width: 100%;
    }
    .dados__endereco i{
        justify-content: center;
        margin: 30px 0 30px 0;
    }
    #dados__contact{
        width: 100%;
    }
    .dados__endereco p{
        text-align: center;
    }
    #dados__contact i{
        justify-content: center;
        padding: 10px 0;
    }
    .footer__copyright p{
        text-align: center;
        padding: 50px 0 20px 0;
    }
    
}
@media (max-width: 480px){
    .footer__container ul li{
        width: 100%;
        text-align: center;
        margin: 10px 0;
    }
}

/*fim footer*/
</style>