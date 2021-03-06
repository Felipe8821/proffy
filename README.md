# 📚 Aplicação Proffy v1.0

<h1 align="center">
    <img alt="Proffy" src="assets/logo.svg" height="100px" />
    <br/>
   <a href="https://nodejs.org/en/" target="_blank" rel="noopener">Node.js</a> | <a href="https://pt-br.reactjs.org" target="_blank" rel="noopener">ReactJS</a> | <a href="https://reactnative.dev" target="_blank" rel="noopener">React Native</a>
</h1>

<p align="center">
  <img alt="Develop by" src="https://img.shields.io/badge/Develop%20by-Gabriel%20Patrola-blue?style=flat&logo=Awesome-Lists">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/gabrielpatrola/proffy?color=informational&style=flat&logo=GitHub-Actions">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/gabrielpatrola/proffy?color=important&style=flat&logo=TypeScript">
  <img alt="Made By" src="https://img.shields.io/badge/Made%20by-RocketSeat-blueviolet?style=flat&logo=Apache-RocketMQ">
  <img alt="Made By" src="https://img.shields.io/github/license/gabrielpatrola/proffy?&style=flat&logo=Google-Sheets">
<p>

<h3 align="center">
  <a href="#-sobre">Sobre</a>
  <span> · </span>
  <a href="#-tecnologias-utilizadas">Tecnologias utilizadas</a>
  <span> · </span>
  <a href="#-como-usar">Como usar</a>
  <span> · </span>
  <a href="#-to-do">To Do</a>
  <span> · </span>
  <a href="#-como-contribuir">Como contribuir</a>
  <span> · </span>
  <a href="#-licença">Licença</a>
</h3>

## 💭 Sobre

Proffy é uma aplicação que tem como objetivo conectar estudantes e professores, dentro dela é fornecido um espaço para que professores registrem sua disponibilidade de horários durante a semana, matérias que leciona, telefone para contato (WhatsApp) e também o custo de sua hora/aula. Já para o estudante é possível encontrar tutores entrar em contato com eles via WhatsApp e também salvar "proffys" em seus favoritos.

A aplicação foi desenvolvida durante a segunda edição da Next Level Week da RocketSeat, entre os dia 03/08/2020 e 09/08/2020, por conta disso foi feita essa homenagem ao dia Nacional dos Profissionais da Educação, que é comemorado em 06 de agosto.

## 👨‍💻 Tecnologias Utilizadas

- <a href="https://reactjs.org/" target="_blank" rel="noopener">React</a> no frontend web;
- <a href="https://reactnative.dev/" target="_blank" rel="noopener">React Native</a> com <a href="https://expo.io/" target="_blank" rel="noopener">Expo</a> no frontend mobile;
- <a href="https://nodejs.org/en/" target="_blank" rel="noopener">Node</a> com <a href="https://expressjs.com/" target="_blank" rel="noopener">Express</a> no backend;
- <a href="https://www.typescriptlang.org/" target="_blank" rel="noopener">TypeScript</a> para tipagem do projeto como um todo.

## ⁉ Como usar

### 🤔 Pré-requisitos

Para conseguir utilizar a aplicação sem nenhum problema é necessário ter:

- O **<a href="https://nodejs.org/en/" target="_blank" rel="noopener">Node.js</a>** instalado no computador para a execução do backend
- Ter em sua máquina o **<a href="https://www.npmjs.com/" target="_blank" rel="noopener">NPM</a>** ou **<a href="https://yarnpkg.com/" target="_blank" rel="noopener">Yarn</a>** para o gerenciamento dos pacotes da aplicação
- **<a href="https://expo.io/" target="_blank" rel="noopener">Expo</a>** instalado de forma global na máquina para a execução da aplicação mobile
- E não menos importante, o **<a href="https://git-scm.com/" target="_blank" rel="noopener">Git</a>** para clonar o repositório em seu computador

### 📝 Passo a passo

Primeiro clone o repositório em seu computador, por meio do terminal utilizando o comando:

1. Clonando o repositório

```sh
  # Clone o repositório
  $ git clone https://github.com/Gabrielpatrola/proffy.git
  # Entre na pasta raiz da aplicação
  $ cd proffy
```

2. Iniciando o Backend

```sh
  # Entre na pasta do backend
  $ cd server
  # Instale as dependências da aplicação
  $ yarn # ou npm install
  # Crie o banco de dados da aplicação
  $ yarn knex:migrate # ou npm run knex:migrate
  # Inicie o servidor
  $ yarn start # ou npm start
```

3. Iniciando o Frontend web

```sh
  # Entre na pasta da aplicação web
  $ cd web
  # Instale as dependências da aplicação
  $ yarn # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start
```

4. Iniciando a aplicação Mobile

```sh
  # Entre na pasta da aplicação mobile
  $ cd mobile
  # Instale as dependências da aplicação
  $ yarn # ou npm install
  # Inicie a aplicação mobile
  $ yarn start # ou npm start
```

## ❗ To Do

Esse projeto não terminou ainda, na versão 2.0 será implementado novas funcionalidades para a aplicação como um todo para tornar ela ainda melhor são elas:

- [ ] Criação das telas seguindo o <a href="https://www.notion.so/Layout-dos-desafios-Proffy-b65b509655194c02b3b4c9d4c74b78b4" target="_blank" rel="noopener">layout do Figma</a>
- [ ] Possibilidade de Autenticação e registro de usuários
- [ ] Funcionalidade de recuperação de senhas
- [ ] Criação do perfil de usuário
- [ ] Splash Screen na aplicação mobile
- [ ] Paginação na listagem de proffys
- [ ] Exibição horários disponíveis dos proffys
- [ ] Possibilidade de salvar seus proffys favoritos
- [ ] Logout da aplicação
- [ ] Deploy da aplicação

Fique atento para as atualizações desse projeto. Não esqueça de deixar uma estrela nesse repositório!

## 💪 Como contribuir

Basta criar um fork do projeto, realizar as modificações que achar necessário e depois fazer um Pull Request.
Toda ajuda é bem vinda, caso veja algum erro, não hesite em contribuir com o projeto!

## 📃 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](/LICENSE) para mais detalhes.

---

<sup> Feito com 💙 por <a href="https://github.com/gabrielpatrola" target="_blank" rel="noopener">Gabriel Patrola</a> por meio da tutoria do <a href="https://github.com/diego3g" target="_blank" rel="noopener">Diego Fernandes</a>, da <a href="https://rocketseat.com.br" target="_blank" rel="noopener">Rocketseat</a>.</sup>
