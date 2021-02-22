# Projeto com TypeORM


## QuickStart com TypeORM

Será criado um projeto simples, com as configurações básicas, com typeorm. Para tanto, será instalado o TypeORM cli e a partir dele será criado um projeto de exemplo. 

O projeto criada serve como referência para incluir o TypeORM em outros projetos já existentes.

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





