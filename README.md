<h1 align="center">
  <img src=".github/logo.svg" alt="Logo">
</h1>

<h3 align="center">
  A simple GitHub Repositories Explorer
</h3>

# Índice

- [Sobre](#sobre)
- [Como Construir Este App do Zero](#tutorial)
- [Tutorial](#tutorial)
- [Stack](#tecnologias-utilizadas)
- [Configurando o Ambiente de Desenvolvimento](#como-usar)
- [Contribua](#como-contribuir)

<a id="sobre"></a>

## :bookmark:  Sobre

O <strong>[GitHub Explorer](https://jimmybastos.github.io/github-explorer/) 📲</strong> é uma aplicação Web que permite salvar e listar repositórios do GitHub, além detalhar suas principais informações.

<details><summary>Screenshots</summary>

</details>

<a id="tecnologias-utilizadas"></a>

## :rocket: Stack

Esta aplicação foi desenolvida com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [ReactJS](https://reactjs.org/)
- [React Router DOM](https://reacttraining.com/react-router/)
- [React Icons](https://react-icons.netlify.com/#/)
- [Styled Components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [Eslint](https://eslint.org/)

<a id="como-usar"></a>

## :fire:  Configurando o Ambiente de Desenvolvimento

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado na máquina
  - Também, é **preciso** ter um gerenciador de pacotes, se você já tem o Node.js, então o **[NPM](https://www.npmjs.com/)** já vai estar disponível.
  - Por fim, é **essencial** seguir as intruções para instalar **[Expo](https://expo.io/)**

1. Faça um clone :

```sh
  $ git clone https://github.com/SpartanHub/little-friend.git
```

2. Executando a Aplicação:

```sh
  # Execute o comando abaixo nas pastas web, app e server
  $ npm install

  ## Crie o banco de dados
  $ cd server
  $ npm run knex:migrate
  $ npm run knex:seed

  # Inicie a API
  $ npm run dev

  # Inicie a aplicação web
  $ cd web
  $ npm start

  # Inicie a aplicação mobile
  $ cd app
  $ npm start
```

<a id="como-contribuir"></a>

## :heavy_check_mark: Como Contribuir

- Faça um Fork desse repositório

- Clone o repositório
```sh
  $ git clone https://github.com/<SEU_USUARIO_GIT>/little-friend.git
```
- Crie um branch com sua feature: `git checkout -b nome-da-feature`

- Comite suas mudanças: `git commit -m 'feat: Breve descrição da feature'`

- Envie a feature: `git push origin nome-da-feature`

## :memo:  License

Esse projeto está sob a licença MIT. Acesse o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<h4 align="center">
    Feito com 💜  by <a href="https://www.linkedin.com/in/jimmybastos" target="_blank">Jimmy Bastos</a>
</h4>
