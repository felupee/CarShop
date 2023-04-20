<p align="center">
  <img src="https://user-images.githubusercontent.com/94487469/233470743-4a6e743b-29ef-44a6-8f44-9c2c83846031.png">
</p>


Olá, seja bem vindo ao repositório do projeto Store Manager! Aqui você irá aprender como instalar e testar esse projeto na sua máquina. Imagine um sistema poderoso e eficiente para gerenciar uma concessionária de veículos. Essa é a minha API em TypeScript! Usando a arquitetura MSC e aplicando os pilares de Programação Orientada a Objetos (POO), eu criei um sistema completo com CRUD para facilitar o gerenciamento de veículos e informações de clientes.

Mas por que usar POO? Simplesmente porque ela oferece uma série de benefícios importantes, como encapsulamento, polimorfismo e herança. Isso torna o código mais organizado, fácil de manter e escalável. E o melhor de tudo: torna o desenvolvimento mais intuitivo e divertido!

E não para por aí. Para conectar o sistema ao banco de dados MongoDB, eu usei o ODM Mongoose, que torna a interação com o banco de dados muito mais fácil e eficiente. Além disso, a arquitetura MSC me permitiu separar as preocupações da aplicação em Model, Service e Controller, tornando o código mais limpo e organizado.

## Como usar :computer: :rocket: 

Usando o Thunder Client ou uma ferramenta de sua escolha, você pode testar todas as rotas disponíveis no projeto.

### Requisitos :clipboard: 

Este projeto pode ser executado de duas formas distintas: a primeira exige a instalação do NODE, enquanto a segunda possibilita o uso do Docker para rodar em uma máquina virtual.

### Instalação :wrench:
#### Com docker:

- Rode o serviço `node` e `db` com o comando `docker-compose up -d.`

Esses serviços irão inicializar um container chamado `car_shop` e outro chamado `car_shop_db`;
A partir daqui você pode rodar o container `car_shop` via CLI ou abri-lo no VS Code.

- Use o comando `docker exec -it car_shop bash` e sigas passos abaixo.
Ele te dará acesso ao terminal interativo do container criado pelo compose, que está rodando em segundo plano.

- Instale as dependências com `npm install`.

#### Sem docker:

- Instale as dependências com `npm install`

Para rodar o projeto desta forma, obrigatoriamente você deve ter o node instalado em seu computador.

### Execução :runner:

Depois de instalar as dependências, basta rodar o comando `npm run dev` para o server ficar online e você poderá fazer requisições a vontade. Sugiro utilizar o `Thunder Client` ou alguma outra ferramenta de sua escolha. 

## Contato :telephone_receiver:

Caso você tenha alguma dúvida sobre esse projeto ou queira da um feedback você encontra minha redes sociais no meu portifólio clicando [aqui](https://felupee.github.io/#contact).
