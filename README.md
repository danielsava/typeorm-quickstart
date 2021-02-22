# Projeto com TypeORM

## Instalação do TypeORM CLI:

Comando abaixo irá instalar o TypeORM cli globalmente:

    $ npm i typeorm -g

<br/>

## Criando o projeto

Abaixo um exemplo para inicializar um projeto com o TypeORM. Para mais opções de base de dados, consultar [documentação oficial](https://typeorm.io)


    $ typeorm init --name typeorm-tutorial --database pg


Instale o driver de conexão com a base de dados. No caso, postgres:

    $ npm i pg --save


<br/>

## Executando o Projeto

Dentro do diretório do projeto criado, execute o `npm install` para instalar todas as dependências:

    $ npm i

<br/>

As configurações da base de dados está dentro do arquivo `ormconfig.json`. Para inicializar o projeto:

    $ npm start





