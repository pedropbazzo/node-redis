# nodejs-redis-example
A simple Node.js Redis 

## To Run index.js

1. Rode um npm install na raiz do projeto

2. Suba um servidor de Redis na sua máquina, conforme explicado no tutorial

3. Rode a aplicação com npm start

## To Run test.js

1. Rode um npm install na raiz do projeto

2. Suba um servidor de Redis na sua máquina

3. Suba um servidor de MySQL na sua máquina e crie um banco de teste

4. Altere a connection string no arquivo test.js para refletir os dados do seu banco

5. Se ainda não possui a tabela com os dados de teste, descomente o respectivo bloco e rode o projeto com npm test

6. Se já tem a tabela com os dados de teste, descomente o trecho da consulta do MySQL para testar somente ela com npm test

7. Querendo testar com Redis, deixe comentado o trecho que vai direto no MySQL e rode com npm test
