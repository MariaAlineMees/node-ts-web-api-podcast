<h1 align="center">
  🎧 Podcast Manager API
</h1>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-features">Features</a> •
  <a href="#-documentação-da-api">API</a> •
  <a href="#-tecnologias">Tecnologias</a> •
  <a href="#-como-executar">Como Executar</a>
</p>

---

## 📺 Sobre o projeto

O **Podcast Manager** é uma aplicação inspirada no modelo "Netflix", projetada para centralizar, organizar e exibir episódios de podcasts em vídeo. O objetivo principal é proporcionar uma experiência fluida onde o usuário pode explorar conteúdos separados por sessões de categorias de seu interesse.

Esta API REST é responsável por fornecer os dados (em formato JSON) que alimentarão a interface front-end da aplicação.

---

## ✨ Features

- [x] **Listagem por Categorias:** Organiza os episódios de podcasts em trilhas/sessões (ex: `saúde`, `fitness`, `mentalidade`, `humor`).
- [x] **Filtro de Busca:** Permite filtrar e buscar episódios específicos baseado no nome do podcast.
- [x] **Dados Enriquecidos:** Retorna o nome do podcast, título do episódio, imagem de capa (thumbnail) e o link para assistir.

---

## 📡 Documentação da API

### `GET /podcasts`

Retorna a lista de episódios de podcasts. É possível enviar o parâmetro com o nome do podcast para filtrar os resultados.

**Exemplo de Resposta:**

```json
[
  {
    "podcastName": "flow",
    "episode": "PROFESSOR HOC - Flow #578",
    "videoId": "cGQV2KIzS6E",
    "cover": "https://i.ytimg.com/vi/cGQV2KIzS6E/maxresdefault.jpg",
    "link": "https://www.youtube.com/watch?v=cGQV2KIzS6E",
    "categories": ["saude", "fitness"]
  },
  {
    "podcastName": "flow",
    "episode": "DJ ARMIN VAN BUUREN - Flow #577",
    "videoId": "C4aE2_RcLCo",
    "cover": "https://i.ytimg.com/vi/C4aE2_RcLCo/maxresdefault.jpg",
    "link": "https://www.youtube.com/watch?v=C4aE2_RcLCo",
    "categories": ["mentalidade", "humor"]
  }
]
```

---

## 🚀 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- **Node.js**
- **TypeScript**

*(Nota: Adicione outras tecnologias aqui, como Express, Fastify, Banco de Dados, etc., de acordo com a evolução do projeto).*

---

## 💻 Como executar

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina o Node.js. Recomenda-se também o uso de um editor de código como o VSCode.

### Rodando a Aplicação

```bash
# Clone este repositório
$ git clone https://github.com/seu-usuario/projeto-app-flow.git

# Acesse a pasta do projeto no terminal/cmd
$ cd projeto-app-flow

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start
```


## 👩🏻‍💻 Projeto desenvolvido por

| Nome | GitHub |
| --- | --- |
| Maria Aline Mees | [MariaAlineMees](https://github.com/MariaAlineMees) |