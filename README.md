# Projeto Cookmaster

## Descrição
Este projeto trata-se de uma aplicação backend utilizando a arquitetura MSC. Neste projeto é possível fazer o cadastro e login de pessoas usuárias, onde apenas essas pessoas poderão acessar, modificar e deletar as receitas que cadastrou. Utilizando JWT Token para autenticação e geração de tokens.

## Habilidades

- Entender o que há por dentro de um token de autenticação;

- Gerar tokens a partir de informações como login e senha;

- Autenticar rotas do Express, usando o token JWT;

- Fazer upload de arquivos em APIs REST;

- Salvar arquivos no servidor através de uma API REST;

- Consultar arquivos do servidor através de uma api REST.

- Realizar testes de integração

## Tecnologias usadas
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## Clonando repositório
> No seu terminal, executar o comando:
```bash
git clone git@github.com:victorcanto/cookmaster.git
``` 
ou
```bash
git clone https://github.com/victorcanto/cookmaster.git
``` 

## Instalando Dependências

> Na pasta raiz do projeto, executar o comando:
```bash
npm install
``` 
## Executando aplicação

> Iniciando servidor MongoDB no Ubuntu
  `sudo systemctl start mongodb.service`
  
> Iniciando servidor MongoDB no Windows
  `C:\Program Files\MongoDB\Server\5.0\bin\mongod.exe" --dbpath="c:\data\db`

> Iniciando servidor MongoDB no Windows
 `brew services start mongodb-community@5.0`

> Na pasta raiz do projeto, para iniciar servidor, executar o comando:
  ```bash
    npm start
  ```
 ## Utilizando aplicação
 
  Usar o [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/download) para realizar as requisições.
  
## Executando Testes

> Na pasta raiz do projeto, executar o comando:
  ```
    npm test
  ```

  Autor: [Victor Canto](https://www.linkedin.com/in/vscanto/)
