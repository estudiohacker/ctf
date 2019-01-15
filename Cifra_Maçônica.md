# Desafio Hackers Mirins

## Cifra Maçônica
----

Neste desafio utilizamos [Cifras maçônicas](https://pt.wikipedia.org/wiki/Cifra_ma%C3%A7%C3%B3nica).
Quando descobrir a resposta, aperte o botão "Já sei a resposta" e digite o número encontrado.

![Cifra Maçônica](Cifra_Maçônica.png)

<button onclick='
  var resposta = prompt("Qual é o número?");
  if (resposta == 694) {
    alert("Parabéns! Vamos para o próximo desafio!");
    window.location.href="Braille";
  } else {
    alert("Resposta errada. Tente novamente.");
  }
'>Já sei a resposta!</button>
