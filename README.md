<p align="center">
  <img src="/images/logo.svg" />
  <br /><br /> 
  Projeto BACKEND realizado para a segunda edição da Next Level Week promovido pela <a href="https://rocketseat.com.br/" target="_blank">Rocketseat</a>.
</p>

## Informações Back-end :scroll:
Esse projeto back-end está codificado em **NodeJS** com **TypeScript**. Este é um servidor com a estrutura que entrega o serviço de APIs Rest.

Nesse projeto contamos com a biblioteca **Express**. Além disso, utilizamos o banco SQLite, porém um fator interessante é a utilização da biblioteca chamada **Knex**, um query builder escrito em JS que pode ser conectado com vários tipos de bancos, evitando assim ter vários scripts para bancos diferentes, este conta também com um sistema de migrations.

Utilizamos o **cors** para controlar acesso de outras fontes de requisições (aqui como projeto prático pessoal, está aberto para geral).

Para auxiliar no desenvolvimento, está sendo utilizado a biblioteca **ts-node-dev**.

## Clone e Instalação :wrench:
Para fazer clone do projeto, basta no console, no diretório que deseja clonar rodar o seguinte comando:

`git clone https://github.com/gabrielgyns/proffy.git`

Após ter feito clone, ainda no mesmo diretório, digite:

`yarn add`

### Scripts
Para iniciar o servidor, basta rodar o código:

`yarn start`

Para realizar o migrate:

`yarn knex:migrate`

Para realizar rollback:

`yarn knex:migrate:rollback`

## Funcionalidades :triangular_ruler:

### Conexões

- Rota para listar o total de conexões realizadas.
- Rota para criar uma nova conexão.

### Aulas

- Rota para criar aulas.
- Rota para listar aulas.
    - Filtrar por matéria, dia da semana e horário;
