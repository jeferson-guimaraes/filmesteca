# Aplicação consumindo API externa TMDb

![GitHub](https://img.shields.io/github/license/jeferson-guimaraes/filmesteca)

## Sobre o projeto

Este projeto foi desenvolvido junto a video aula: [Projeto de filmes com react e API do TMDB (React Router, React Hooks)](https://www.youtube.com/watch?v=XqxUHVVO7-U&ab_channel=MatheusBattisti-HoradeCodar) do professor [Matheus Battisti](https://github.com/matheusbattisti). Participei desta aula com intuíto de conhecer melhor as tecnologias utilizadas.

O projeto consiste em uma aplicação que exibe os dez filmes melhor raqueados segundo a [TMDb](https://developer.themoviedb.org/docs/getting-started), trazendo informações sobre cada um deles.

### Funcionalidades

* Listar filmes melhor raqueados
* Buscar filmes por título
* Obter detalhes de um filmes específico

### Tecnologias utilizadas

* Node.js
* React
* Fetch API
* CSS
* Vite
* Dotenv

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/pt)

Além disso, é bom ter um editor para trabalhar com o código, como o [VSCode](https://code.visualstudio.com/).

### Como executar o projeto

#### 1. Clone o repositório
```
git clone https://github.com/jeferson-guimaraes/filmesteca
```

#### 2. Acesse o diretório do projeto
```
cd filmesteca
```

#### 3. Instale as dependências
```
npm install
```

#### 4. Configure as variáveis de ambiente
Renomeie o arquivo _.env-exemple_ para _.env_ e coloque sua chave da API

>**Obs:** É possível conseguir uma chave da API gratuitamente fazendo o cadastro no site [TMDb](https://developer.themoviedb.org/docs/getting-started)

```
VITE_API_KEY=api_key=your_api_key_here
```

#### 5. Execute a aplicação
```
npm run dev
```
