# Desafio Hackers Mirins

## Sistema binário
----

Os computadores utilizando números binários para tudo, inclusive para representar letras! 
Utilizando um [Sistema Binário](https://pt.wikipedia.org/wiki/Sistema_de_numera%C3%A7%C3%A3o_bin%C3%A1rio) e
a tabela [ASCII](https://pt.wikipedia.org/wiki/ASCII), tente resolver o desafio.
Quando conseguir, aperte o botão "Já sei a resposta" e digite o número encontrado.

    01100011 01100101 01101110 01110100 01101111 00100000 01100101 00100000 01101110 01101111 01110110 01100101

<button onclick='
  var resposta = prompt("Qual é o número?");
  if (resposta == 109) {
    alert("Parabéns! Vamos para o próximo desafio!");
    window.location.href="Código_Morse";
  } else {
    alert("Resposta errada. Tente novamente.");
  }
'>Já sei a resposta!</button>
