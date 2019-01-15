# Desafio Hackers Mirins

## Braille
----

Agora vamos resolver um desafio escrito em [Braille](https://pt.wikipedia.org/wiki/Braille).
Quando descobrir a resposta, aperte o botão "Já sei a resposta" e digite o número encontrado.

    ⠎ ⠑ ⠞ ⠑ ⠉ ⠑ ⠝ ⠞ ⠕ ⠎   ⠑   ⠉ ⠊ ⠝ ⠉ ⠕

<button onclick='
  var resposta = prompt("Qual é o número?");
  if (resposta == 705) {
    alert("Parabéns! Vamos para o próximo desafio!");
    window.location.href="Sistema_Hexa";
  } else {
    alert("Resposta errada. Tente novamente.");
  }
'>Já sei a resposta!</button>
