<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 03: Conceitos do ReactJS
</h3>


## Features
Para o desenvolvimento do projeto foi utilizada uma stack com as seguintes tecnologias:

- 💹 **React Js** — Web framework que permite utilizar HTML, CSS e Imagem dentro do JavaScript;
- 💹 **Axios** - é um cliente HTTP, que funciona tanto no browser quanto em node
## Desafio

Durante as aulas de Front-end com ReactJs foi abordado os seguintes temas:

- ** `Conceito ReactJs`**
- ** `Configurando Babel`**
- ** `Configurando Webpack`**
- ** `Componentização`**
- ** `Propriedades`**
- ** `Estado e Imutabilidade`**
- ** `Importando Css e Imagens`**
- ** `Listando Projetos da API`**
- ** `Cadastando Projetos`**

## Requisitos

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na sua API.

- **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

## Getting started
yarn dev

### Instalação
Clone o projeto em seu computador. Para instalar as dependências e executar o **Servidor** (modo dev) execute:
```bash
https://github.com/Bruno-Goudric/conceito-reactjs.git 
cd conceito_node_js
yarn install
yarn start
```

### Validando os Testes da Aplicação
Clone o projeto em seu computador. Para instalar as dependências e executar o **Servidor** (modo test) execute:

```bash
  https://github.com/Bruno-Goudric/conceito-reactjs.git 
  cd conceito_node_js
  yarn install
  yarn test
```

### Específicação dos testes

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Caso você tenha dúvidas quanto ao que são os testes, e como interpretá-los, dé uma olhada em **[nosso FAQ](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/faq-desafios).**

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.
