# Desafio Hackers Mirins

## Estereograma
----

Uma forma inusitada de esconder uma informação é através do uso de [Estereogramas](https://pt.wikipedia.org/wiki/Estereograma).
Você vai precisar de bastante paciência para resolver este desafio.
Quando descobrir a resposta, aperte o botão "Já sei a resposta" e digite o número encontrado.

![Estereograma](Estereograma.png)

<button onclick='
  var resposta = prompt("Qual é o número?");
  if (resposta == 0) {
    alert("Parabéns! Vamos para o próximo desafio!");
    window.location.href="Faça_Você_Mesmo";
  } else {
    alert("Resposta errada. Tente novamente.");
  }
'>Já sei a resposta!</button>
