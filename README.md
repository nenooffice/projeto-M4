# Hamburgueria Blue

Projeto desenvolvido para entrega do Módulo 4 da Blue EdTech.
<br/>
Neste projeto você encontrará conceitos de autenticação, filtragem de buscas, documentação de projetos e bancos de dados relacionais.

## Pré-requisitos

- **Node** com versão superior ou igual que 16.15.0 - [Node Download](https://nodejs.org/pt-br/download/)
- **NPM** com versão superior ou igual que 8.5.5 - [Npm Download](https://www.npmjs.com/package/download)
- **Nest.js** com versão superior ou igual que 8.5.5 - [Nest Download](https://docs.nestjs.com/)
- **PostgreSQL** com versão superior ou igual que 8.2.6 - [PostgreSQL Download](https://www.postgresql.org/download/)

## Instalação

Clone esse projeto em seu computador com o comando (Chave SSH necessária):

```bash
#!/bin/bash
$ git clone git.github.com/nenooffice/projeto-M4.git
```

Acesse a pasta do projeto:

```bash
#!/bin/bash
$ cd projeto-M4
```

Instale as dependências com o seguinte comando:

```bash
#!/bin/bash
$ npm install
```

## Execução

Após ter instalado as dependências, use o seguinte comando para rodar o projeto em um servidor local:

```bash
#!/bin/bash
$ npm run start:dev
```

Para conseguir trabalhar com o banco de dados você deverá criar um arquivo .env e adicionar uma url de conexão com seu Postgres local com a chave DATABASE_URL.

```md
DATABASE_URL="postgresql://postgres:admin@localhost:5432/projeto1"
```

## Funcionalidades

Para acessar a lista de endpoints e funcionalidades da aplicação, acesse nossa documentação do [Swagger](http://localhost:3333/docs/#/), lá você poderá testar todas as rotas.

Você também pode analisar nosso <a href="./db.pdf" download>Diagrama de Relacionamento de Entidades</a>

## Autor

- Eugenio Bufalo Rodrigues

## Contribuição

Sinta-se a vontade para entrar em contato comigo caso tenha qualquer sugestão de melhoria no projeto

<div>
<a href="https://www.linkedin.com/in/eugenio-neno-rodrigues/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href="https://instagram.com/lordn3no/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href = "mailto:nenodev.contato@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>

## Licença

- MIT License (MIT)

