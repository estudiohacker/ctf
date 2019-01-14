# Desafio Hackers Mirins

## Cifra de César
----

Temos mais um desafio aqui, mas desta vez utilizando a [Cifra de César](https://pt.wikipedia.org/wiki/Cifra_de_C%C3%A9sar). Quando descobrir a resposta, aperte o botão "Já sei a resposta" e digite o número encontrado.

    Hfsnsbhcg s jwbhs s ia.

Esta tabela vai ajudá-lo a desvendar este desafio.

![Cifra de César](Cifra_de_César.png)

<button onclick='
  var resposta = prompt("Qual é o número?");
  if (resposta == 321) {
    alert("Parabéns! Vamos para o próximo desafio!");
    window.location.href="Cifra";
  } else {
    alert("Resposta errada. Tente novamente.");
  }
'>Já sei a resposta!</button>
