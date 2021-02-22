# Projeto com TypeORM

Projeto de referência com as configurações básicas do typeorm.

## QuickStart com TypeORM

Será criado um projeto simples, com as configurações básicas, através do cli do TypeORM. É o mesmo projeto e os mesmos passos descritos no `Quick Start` da (documentação oficial)[https://typeorm.io]

Este projeto foi criado como referência das configurações básicas para um projeto funcionar com TypeORM, como por exemplo as opções do `tsconfig.json` para utilizar as anotações (decorators em TypeScript) (`"emitDecoratorMetadata": true, "experimentalDecorators": true `), as dependências em `package.json` e as configurações do TypeORM em `ormconfig.json`. 

<br/>

### Instalação do TypeORM CLI:

Comando abaixo irá instalar o TypeORM cli globalmente:

    $ npm i typeorm -g

<br/>

### Criando o projeto

Abaixo um exemplo para inicializar um projeto com o TypeORM. Para mais opções de base de dados, consultar [documentação oficial](https://typeorm.io)


    $ typeorm init --name typeorm-tutorial --database pg


Instale o driver de conexão com a base de dados. No caso, postgres:

    $ npm i pg --save


<br/>

### Executando o Projeto

Dentro do diretório do projeto criado, execute o `npm install` para instalar todas as dependências:

    $ npm i

<br/>

As configurações da base de dados está dentro do arquivo `ormconfig.json`. Para inicializar o projeto:

    $ npm start





