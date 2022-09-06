# Aula-1---Desafio-1
Desafio da Estilização

CÓDIGO COMPLETO:

HTML5

<html>
  <head>
    <title> Imersão Dev Alura - Aula 01</title>
  </head>
  <body>
    <div class="container">
      <h1 class="page-title">
      Promoção Imperdível!</h1>
      <p class="page-subtitle">
      Corram! Tem apenas 5 unidades no estoque!
      </p>
      <br>
      <h2 class="page-subtitle"><b>
      Calculadora Científica por apenas R$ 20,00.</b>
      </h2>
      <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/logo-imersao-conversor-de-moedas.svg" class="page-logo" alt="Calculadora Científica">
    </div>
    <a href="https://alura.com.br/" target="_blank">
    <img src="https://www.alura.com.br/assets/img/home/alura-logo.svg" alt="Imersão Dev" class="alura-logo">
    </a>
   <p class="page-subtitle">
      Calcule a sua nota:
   </p>
 <script>
 document.write("<h4> Notas Bimestrais: ");
 document.write(" 9 + 7 + 6 + 10 = ");
 document.write(9+7+6+10);
 document.write("<h4> Média: ");
 document.write((9+7+6+10)/4);
</script>
  </body>
</html>


CSS3

body {
  font-family: "Roboto Mono", monospace;
  min-height: 400px;
  background-image: url("https://images-americanas.b2w.io/spacey/acom/2022/01/20/calculadora_cientifica-d35333d41de9.png");
  background-color: rgb(232, 4, 4);
  background-size: 80vh;
  background-position: center bottom;
  background-repeat: no-repeat;
}

.container {
  text-align: center;
  padding: 20px;
  height: 100vh;
}

.page-title {
  color: #ffffff;
  margin: 0 0 5px;
}

.page-subtitle {
  color: #ffffff;
  margin-top: 5px;
}

.page-logo {
  width: 200px;
}

.alura-logo {
  width: 40px;
  position: absolute;
  top: 10px;
  right: 10px;
}
write {
  width: 200px;
}


JAVASCRIPT

var nome = "Maria"
var notaDoPrimeiroBimestre = 9
var notaDoSegundoBimestre = 7
var notaDoTerceiroBimestre = 6
var notaDoQuartoBimestre = 10

var notaFinal = (notaDoPrimeiroBimestre + notaDoSegundoBimestre + notaDoTerceiroBimestre + notaDoQuartoBimestre) / 4

var notaFixada = notaFinal.toFixed(1)

console.log("Bem vindo " + nome)
console.log("Você tirou nota " + notaFixada)

alert('Corram tem 5 unidades no estoque!');
