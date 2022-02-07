<template>
  <div id="app">
    <section class="menuBackground">
    <div class="container w100 spaceBetween">
      <div class="menu">
        <img style="" src="">WARREN
      </div>
      <div class="menu">INVESTIR</div>
      <div class="menu">APRENDER</div>
      <div class="menu">PLANOS WARREN</div>
      <div class="menu">SOBRE</div>
      <div class="menu">COMO FUNCIONA</div>
      <div class="menu">
        <Button texto="ABRIR SUA CONTA" class="buttonBlack" :onClick="handleAlert" />
      </div>
    </div>
  </section>
  <section class="cardBackground">
    <div class=" container w100">
      <div class="title1 textWhite">
        <b>Lorem ipsum dolor sit, consectetur adipiscing elit.</b>
      </div>
      <div class="textWhite spaceBetweenText">Consequat leo, nec, sit sociis tellus ut amet.</div>
      <div>
        <Button texto="CRIAR CONTA" class="buttonBlack" :onClick="handleAlert" />
      </div>
    </div>
  </section>
  <section class="card2Background">
    <div class="w100 container">
      <div>
        <div class="w50 inline divTop">
          <div class="w50 inline divImgCard">
            <div class="ImgCard">&nbsp;</div>
          </div>
        </div><!--
      ---><div class="w50 inline">
          <div class="w50 inline">
            &nbsp;
          </div><!--
        ---><div class="w50 inline">
            <div><h2>Lorem ipsum</h2></div>
            <div>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna blandit urna sit in dictum aliquam. Tempus, viverra tincidunt risus eget aliquam ipsum.
              <hr class="hrColor" />
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna blandit urna sit in dictum aliquam. Tempus, viverra tincidunt risus eget aliquam ipsum.
            </div>
            <div class="spaceBetweenText">
              <Button texto="SUA CARTEIRA" class="" :onClick="handleAlert" />
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="w50 inline divTop">
          <div class="w50 inline">
            <div><h2>Lorem ipsum</h2></div>
            <div>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna blandit urna sit in dictum aliquam. Tempus, viverra tincidunt risus eget aliquam ipsum.
              <hr class="hrColor" />
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna blandit urna sit in dictum aliquam. Tempus, viverra tincidunt risus eget aliquam ipsum.
            </div>
            <div class="spaceBetweenText">
              <Button texto="SUA CARTEIRA" class="" :onClick="handleAlert" />
            </div>
          </div>
        </div>
        <div class="w50 inline">
          <div class="divImgCard ImgCard" style="float: right;">&nbsp;</div>
        </div>
      </div>
    </div>
  </section>
  <section class="card3Background">
    <div class="w100 container textWhite">
      <div class="inline w50 textRight">
        <h1>Investir é sobre você</h1>
      </div>
      <div class="inline w50 textRight">
        <Button texto="SUA CARTEIRA" class="buttonBlack" :onClick="handleAlert" />
      </div>
    </div>
  </section>
  <section class="bottomBackground">
    <div class="w100 container textCentered textWhite bottomText">
      <div class="inline w25 divTop">
        <h3>Sobre</h3>
        <div>
          Quem Somos<br />
          Como Funciona<br />
          Planos Warren<br />
          Warren Magazine<br />
          Warren Invites<br />
          Trabalhe Conosco<br />
          Impresa
        </div>
      </div><!--
    ---><div class="inline w25 divTop">
        <h3>Investir</h3>
        <div>
          Bolsa<br />
          Carteiras<br />
          Conta<br />
          Home Broker<br />
          Produtos de Investimento<br />
          Previdência<br />
          Conta PJ<br />
          Warren Pro
        </div>
      </div><!--
    ---><div class="inline w25 divTop">
        <h3>Aprender</h3>
        <div>
          Warren Educação<br />
          In Company<br />
          Desintoxicação Financeira<br />
          Warren Life Express<br />
          Como Investir na Bolsa<br />
          Mercado em Análise
        </div>
      </div><!--
    ---><div class="inline w25 divTop">
        <h3>Fale Conosco</h3>
        <div>
          Acesse nosso FAQ<br />
          meajuda@warren.com.br<br />
          Acesse o chat<br />
          Acesse o WhatsApp<br />
          LOREM IPSUM<br />
          LOREM IPSUM
        </div>
      </div>
    </div>
  </section>
  </div>
</template>


<script>
import Button from '../components/Button.vue'

export default {
  name: 'Home',
  components: {
    Button
  },
  methods: {
    handleAlert() {
      alert("fui pressionado")
      return 'fui';
    },
    handleAlert2() {
      alert("fui pressionado 2")
      return 'fui';
    }
  }
}
</script>

<style>
  body {
    margin: 0;
  }

  .textCentered {
    text-align: center;
  }

  .textRight {
    text-align: right;
  }

  .textWhite {
    color: white;
  }

  .spaceBetween {
    display: flex;
    justify-content: space-between;
    text-align: center;
  }

  .spaceBetweenText {
    padding: 30px 0;
  }

  .inline {
    display: inline-block;
  }

  .menu {
    display: inline;
    width: 100%;
    margin: auto auto;
    font-weight: bold;
    color: white;
  }

  .w100 {
    width: 100%;
  }

  .w50 {
    width: 49.99%;
  }

  .w25 {
    width: 25%;
  }

  .w10 {
    width: 10%;
  }

  .container {
    max-width: 1140px;
    margin: 0 auto;
  }

  .divTop {
    vertical-align: top;
  }

  .divImgCard {
    width: 70%;
  }

  .ImgCard {
    background: #D4D4D4;
    height: 430px;
  }

  .menuBackground {
    background: #E02B57;
    padding: 5px 0 5px;
  }

  .cardBackground {
    background: #6E6E6E;
    background: linear-gradient(180deg, #E02B57 0%, rgba(224, 43, 87, 0.994792) 17.71%, rgba(224, 43, 87, 0) 100%);

    padding: 80px 0 80px 0;
  }

  .card2Background {
    padding: 80px 0 80px 0;
  }

  .card3Background {
    padding: 80px 0;
    background: #E02B57;

  }

  .bottomBackground {
    padding: 80px 0;
    background: #2F2F33;
  }

  .bottomText {
    line-height: 25px;
  }

  .title1 {
    font-size: 69px;
  }

  button {
    border-radius: 100px;
    background: #EE2E5D;
    color: white;
    padding: 15px;
    border: none;
  }

  .buttonBlack {
    background: #2F2F33;
  }

  .hrColor {
    border: 1px solid #E02B57;
  }
</style>
