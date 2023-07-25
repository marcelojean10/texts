🇧🇷  Hoje vou escrever um pouco sobre o padrão de projeto Façade (Fachada).

Esse padrão de projeto deveria ser muito utilizado em sistemas legados/monólitos. 😫

O que é o padrão Façade?
Façade é um padrão simples que fornece uma interface alternativa para um objeto.
É muito útil em casos de reengenharia e refatoração.

Com o javascript você consegue tratar eventos do navegador com algumas funções como essas:
stopPropagation()
Captura o evento e não o deixa ser transmitido aos elementos pai.
preventDefault()
Não permite que o navegador faça a ação padrão (seguir link/disparar um formulário).

Temos dois métodos com propósitos diferentes, e aí, que vem a FAÇADE. Você criaria um método auxiliar que invocaria as duas funções.
 
function stop() {
 stopPropagation();
 preventDefault()
}

Isso é uma façade, que simples né.


Ref: book javascript patterns