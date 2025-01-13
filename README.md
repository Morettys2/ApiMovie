# 🎥 Movie Search Project

Este é um projeto de pesquisa de filmes desenvolvido com [Next.js](https://nextjs.org/) e consumindo a API do [The Movie Database (TMDb)](https://www.themoviedb.org/). O objetivo do projeto é permitir que os usuários pesquisem filmes e vejam informações detalhadas, como notas e descrições.

## ✨ Funcionalidades

- 🔍 Pesquisa de filmes por título.
- 📝 Exibição de informações como:
  - 🎬 Título do filme.
  - 📖 Sinopse.
  - ⭐ Nota (rating).
  - 🗓️ Data de lançamento.
- 📱 Interface responsiva e amigável.

## 🛠️ Tecnologias Utilizadas

- **⚡ Next.js**: Framework React para renderização do lado do servidor (SSR) e aplicações web modernas.
- **🎞️ API do TMDb**: Fonte de dados para informações sobre filmes.
- **🎨 CSS/Styled Components/Tailwind (escolha uma)**: Para estilização da interface.

## 📋 Requisitos

- 📦 Node.js 18+.
- 🔑 Chave de API do TMDb (vá em [TMDb](https://www.themoviedb.org/) e crie uma conta para obter sua chave de API).

## 🚀 Instalação e Execução

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências:

   ```bash
   npm install
   # ou
   yarn install
   ```

3. Crie um arquivo `.env.local` na raiz do projeto com a seguinte configuração:

   ```env
   NEXT_PUBLIC_TMDB_API_KEY=SuaChaveDeAPI
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   # ou
   yarn dev
   ```

5. Abra [http://localhost:3000](http://localhost:3000) no navegador para visualizar o projeto.

## 📂 Estrutura do Projeto

- **📁 /pages**: Contém as páginas do Next.js.
- **📁 /components**: Componentes reutilizáveis da interface.
- **📁 /styles**: Arquivos de estilização (CSS, Styled Components ou Tailwind).
- **📁 /utils**: Funções utilitárias, como chamadas para a API do TMDb.

## 🌟 Melhorias Futuras

- 🔧 Adição de filtros, como gênero e idioma.
- 🌀 Integração com bibliotecas de animações (ex.: Framer Motion).
- 🎥 Exibição de trailers dos filmes.
- ❤️ Suporte para criação de listas de favoritos.

