
# Exercício de Node.js
<h1 align="center">:file_cabinet: Desafio02-Node.js-Rocketseat</h1>

## :memo: Descrição
Exercício de Node.js, Trabalhando com middlewares, gereciamento de 'todos' (tarefas).

## :books: Funcionalidades

[x]Deve ser capaz de encontrar o usuário pelo nome de usuário no cabeçalho e passá-lo para 'request.user'<br>
[x]Deve permitir que o usuário crie uma nova tarefa quando estiver no plano gratuito e tiver menos de dez tarefas<br>
[x]Deve ser capaz de permitir que o usuário crie infinitos novos 'todos' quando estiver no plano Pro<br>
[x]Deve ser capaz de colocar o usuário e 'todo' no pedido quando ambos saem<br>
[x]Deve ser capaz de encontrar o usuário pelo parâmetro de rota id e passá-lo para 'request.user'<br>
[ ]Deve ser capaz de deletar um todo<br>

## :books: Regras de negócio

[x]Não permitir que o usuário crie um novo 'todo' quando não for Pro e já tiver dez 'todos'<br>
[x]Não permitir encontrar um usuário não existente pelo nome de usuário no 'headers'<br>
[x]Não permitir colocar o usuário e 'todo' o pedido quando o usuário não existe<br>
[x]Não permitir colocar o usuário e o 'todo' na solicitação quando o id do 'todo' não é uuid<br>
[x]Não permitir colocar o usuário e o 'todo' na solicitação quando o 'todo' não existe<br>
[x]Não permitir passar o usuário para 'request.user' quando ele não existe<br>
[x]Não permitir atualizar um 'todo' não existente<br>

## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
```
git clone git@github.com:ur4sh1/Desafio02-Node.js-Rocketseat.git
```
Instalar o yarn
```
yarn install
```
Executar o projeto
```
yarn dev
```

## :wrench: Histórico de comandos
Executar testes dos endpoints
```
yarn test
```




