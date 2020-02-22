<h1 align="center">
  Repo Show
</h1>

<p>O Repo Show é uma aplicação para consulta de repositórios utilizando a (maravilhosa) API pública do GitHub.</p>

<p align="center">
  <a href="https://github.com/douglasthmz">
    Made by Douglas Thomaz
  </a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

## Sobre a aplicação

Esta aplicação foi desenvolvida durante o BootCamp GoStack, da [RocketSeat](https://rocketseat.com.br/gostack).

### **Um pouco sobre as ferramentas**

Para a criação da aplicação utilizei o framework do Facebook, o [React](https://pt-br.reactjs.org/), além dos seguintes plugins:

- [Axios](https://github.com/axios/axios), para as requisições à [API do GitHub](https://developer.github.com/v3/)
- [ESLint](https://eslint.org/) + [Prettier](https://prettier.io/) + [EditorConfig](https://editorconfig.org/) para padronização e correção de código (utilizei o padrão de código do AirBnb);

### **Funcionalidades**

Abaixo estão descritas as funcionalidades da aplicação.

### **1. Busca de um user/repo**

Utilizando o campo de texto, o usuário digita o user/repo que deseja monitorar, como por exemplo [facebook/react](https://github.com/facebook/react).

Ao fazer a busca, um item é listado logo abaixo do formulário, contendo o user/repo inserido pelo usuário, e um link de detalhes, que explicaremos a seguir.


### 2. Página de detalhes

Ao clicar no botão **Detalhes**, a aplicação nos redireciona para outra página, uma que nos mostra o **avatar** do criador do repositório, assim como o **nome** e a **description** do repo.

Abaixo, temos uma listagem dos ultimos 5 **issues** do repositório, em que ao clicar no **titulo** da issue, o usuário é levado diretamente para a página do GitHub referente à issue clicada.




