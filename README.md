<h1 align="center"> Challenge Amigo Secreto </h1>
<p align = "center">
<img alt="Static Badge" src="https://img.shields.io/badge/Desafio-8A2BE2">
<img alt="Static Badge" src="https://img.shields.io/badge/Iniciante-%23008000">
<img alt="Static Badge" src="https://img.shields.io/badge/L%C3%B3gica%20de%20Programa%C3%A7%C3%A3o-0000FF">
</p>
:small_blue_diamond: Status do Projeto: :heavy_check_mark: Concluído 

## Tópicos 
:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)
:small_blue_diamond: [Funcionalidades](#funcionalidades)

## Descrição do projeto 
<p align="justify">
 Resolução do desafio obrigatório proposto pela Oracle One para avaliar o desempenho da aprendizagem da lógica de programação utilizando JavaScript. Neste desafio, desenvolvi uma aplicação que permite aos usuários inserir nomes de amigos em uma lista que é exibida na tela para, em seguida, quando o usuário clicar no botão "Sortear Amigo" realizar um sorteio aleatório entre os nomes da lista e determinar quem é o "amigo secreto", exibindo o resultado na tela.
</p>

## Funcionalidades
:heavy_check_mark: Função para adicionar nomes
<p align ="justify">
O projeto começa com a declaração uma variável do tipo array, que armazenará os nomes dos amigos inseridos. Seguido de uma função que captura o valor do campo de entrada utilizando "document.getElementById" para obter o texto inserido pelo usuário. A função também valida a entrada verificando se o campo estiver vazio, e caso esteja, exibe um alerta com a mensagem de erro: "Por favor, insira um nome." Em seguida, ela atualiza o array de amigos: Se o valor for válido, o adiciona ao array que armazena os nomes dos amigos usando o método .push(). Por fim, limpa o campo de entrada após adicionar o nome, redefine o campo de texto para uma string vazia.
</p>

:heavy_check_mark: Função para atualizar a lista de amigos 
<p align ="justify">
Uma função que percorra o array amigos com um loop e adiciona cada nome como um elemento "Li" dentro de uma lista HTML e usa "innerHTML" para limpar a lista antes de adicionar novos elementos para garantir que não haja duplicados ao atualizar. Ela também obtem o elemento da lista utilizando "document.getElementById()" para selecionar a lista onde os amigos serão exibidos. 
</p>

:heavy_check_mark: Função para sortear os amigos 
<p align ="justify">
 A função valida que há amigos disponíveis antes de sortear, verifica se o array amigos não está vazio. Em seguida, gera um índice aleatório usando "Math.random()" e "Math.floor()" para selecionar um índice aleatório do array. Obtem então, o nome sorteado usando o índice aleatório para acessar o nome correspondente no array. Por fim, mostra o resultado atualizando o conteúdo do elemento de resultado usando "document.getElementById()" e "innerHTML" para exibir o amigo sorteado.
</p>

## Observações
O código JS foi desenvolvido em resposta ao desafio, todo o código HTML e CSS foi fornecido pela Oracle Next Education em parceria com a Alura.

Copyright :copyright: 2025 - Desafio Amigo Secreto
  

