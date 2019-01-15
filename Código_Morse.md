# Desafio Hackers Mirins

## Código Morse
----

Antigamente utilizávamos o Código Morse para enviar mensagens a longas distâncias. 
Utilizando uma tabela de conversão, tente resolver o desafio a seguir.
Quando conseguir, aperte o botão "Já sei a resposta" e digite as três letras encontradas!

    ... --- ...

<button onclick='
  var resposta = prompt("Qual são as três letras encontradas?");
  if (resposta == "SOS") {
    alert("Parabéns! Vamos para o próximo desafio!");
    window.location.href="Estereograma";
  } else {
    alert("Resposta errada. Tente novamente.");
  }
'>Já sei a resposta!</button>
