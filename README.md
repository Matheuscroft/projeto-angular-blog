# 🦸‍♂️ DC BLOG

Projeto de Blog com página inicial, cards com as matérias e a página do conteúdo da notícia.  
Este projeto foi criado com [Angular CLI](https://github.com/angular/angular-cli) versão 18.2.5.  

## 📌 Instalação

1. **Instale o Angular CLI** se ainda não tiver:  
   ```sh
   npm install -g @angular/cli
   ```
2. **Clone o repositório:**  
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd nome-do-projeto
   ```
3. **Instale as dependências:**  
   ```sh
   npm install
   ```
4. **Execute o servidor de desenvolvimento:**  
   ```sh
   ng serve
   ```
   Acesse [`http://localhost:4200/`](http://localhost:4200/) no navegador. 🌍

## 🛠 Criando um novo projeto Angular

Caso queira criar um projeto do zero, execute:  
```sh
ng new meu-blog
cd meu-blog
ng serve
```

## 📂 Estrutura do Projeto

Dentro da pasta `src/app`, temos as seguintes pastas:

- 📌 `components/` - Contém os componentes reutilizáveis:
  - **big-card**: Componente de destaque para exibir grandes conteúdos.
  - **menu-bar**: Barra de navegação do blog.
  - **menu-title**: Título principal do menu.
  - **small-card**: Pequeno card para prévias de conteúdo.

- 📌 `pages/` - Contém as páginas principais:
  - **home**: Página inicial do blog.
  - **content**: Página que exibe o conteúdo de um post.

- 📌 `data/` - Contém os dados fake usados no blog.

## 🎨 Criando Componentes e Páginas

Para criar novos componentes:  
```sh
ng generate component components/nome-do-componente
```

Para criar novas páginas:  
```sh
ng generate component pages/nome-da-pagina
```

## 📝 Exemplo de Dados Fake

Os dados estão armazenados em `src/app/data/dataFake.ts` e são usados para exibir os posts no blog:

```typescript
export const dataFake = [
    {
      "id":"1",
      "title": "NOVO AQUAMAN EM BREVE?",
      "description": "O que a DC fala sobre um terceiro filme do herói.",
      "photoCover":"https://www.otempo.com.br/content/dam/otempo/editorias/entretenimento/filmes-e-series/2023/9/entretenimento-aquaman-2-veja-sinopse-elenco-e-trailer-do-filme-1708758077.jpeg"
    },
    {
      "id":"2",
      "title": "Série da Arlequina é renovada",
      "description": "Série é um grande sucesso entre os fãs.",
      "photoCover":"https://cinepop.com.br/wp-content/uploads/2023/01/Harley-Quinn-Valentines-Day-Special-2023.jpg"
    },
    {
      "id":"3",
      "title": "Henry Cavill pode voltar a ser Superman",
      "description": "Fortes rumores indicam a volta do ator.",
      "photoCover":"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQrKC4VseUqi5UbGLPU8SdbJEnXVcTw686rpQ&s"
    },
    {
      "id":"4",
      "title": "Filme da Liga da Justiça em produção",
      "description": "Trata-se da continuação do primeiro filme.",
      "photoCover":"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ6jDJyCJaD6XOnPPGi56J0sp8K-Sc5WAI9Cw&s"
    }
];
```

## ❓ Ajuda

Para mais informações, consulte a [documentação do Angular CLI](https://angular.dev/tools/cli). 📚
