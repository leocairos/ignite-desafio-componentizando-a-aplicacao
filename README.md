<h1 align="center">
    <img alt="Ignite ReactJS" title="Ignite ReactJS" src="./.github/ignite.png" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/leocairos/ignite-desafio-componentizando-a-aplicacao?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/leocairos/ignite-desafio-componentizando-a-aplicacao">

  <a href="https://github.com//leocairos/ignite-desafio-componentizando-a-aplicacao/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/leocairos/ignite-desafio-componentizando-a-aplicacao">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/leocairos/ignite-desafio-componentizando-a-aplicacao/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/leocairos/ignite-desafio-componentizando-a-aplicacao?style=social">
  </a>

  <a href="https://www.linkedin.com/in/leonardo-sampaio-cairo-54a74756/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin&labelColor=blue">
  </a>
</p>

# 🚀 Sobre

O Ignite é um programa de aceleração para devs desenvolvido pela [Rocketseat](https://rocketseat.com.br/).


# 💻 Sobre o desafio

Nesse desafio, foi criada uma aplicação para treinar o que se aprendeu até agora no ReactJS dentro do Ignite.

Essa é uma aplicação onde o seu principal objetivo é refatorar uma página para listagem de filmes de acordo com gênero. 

A aplicação já estava totalmente funcional mas grande parte do seu código está diretamente no arquivo `App.tsx`. Para resolver isso da melhor forma, é foi dividir a aplicação em **pelo menos** duas partes principais: sidebar e o conteúdo principal que possui o header e a listagem de filmes.

- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já deve começar como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve mudar dinamicamente.

## Se preparando para o desafio

Para esse desafio, além dos conceitos vistos em aula foram utilizadas algumas coisa novas para deixar a nossa aplicação ainda melhor. 

### Fake API com JSON Server

Foi utilizado o JSON Server para simular uma API que possui as informações de gêneros e filmes. 

Navegue até a pasta criada, abra no Visual Studio Code e execute os seguintes comandos no terminal:

```bash
yarn
yarn server
```

Perceba que ele iniciará uma fake API com os recursos `/genres` e `/movies` em `localhost` na porta `3333` a partir das informações do arquivo [server.json](https://github.com/rocketseat-education/ignite-template-componentizando-a-aplicacao/blob/main/server.json) localizado na raiz do seu projeto. Acessando essas rotas no seu navegador, você consegue ver o retorno das informações já em JSON.

## 📝 Licença

Este projeto esta sob a licença MIT.

Feito com ❤️ por [Leonardo Cairo](https://www.linkedin.com/in/leonardo-sampaio-cairo-54a74756/)!
