<h1 align="center">
  :superhero_man: ComicsExplorer :closed_book:
</h1>

<h4 align="center">
  Um desafio front-end desenvolvido por <a href='https://github.com/TiagoDiass'>@TiagoDiass</a> onde pessoas podem procurar por livros usando a API da Marvel
</h4>

<p align="center">
  <img alt="Repo's top languages" src="https://img.shields.io/static/v1?label=Main%20technologies&message=React%2FNext.js%2FTypeScript&style=for-the-badge&color=2b7489&labelColor=000000">
</p>

<p align="center">
  <a href="#final-result">Resultado final</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#features">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tests">Testes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#deploy">Deploy</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-run">Como rodar</a>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;![](screenshots/preview.gif)

<h2 align="center">
  <a href="https://south-frontend-challenge.vercel.app/" target="_blank">
    Demo na Vercel
  </a>
</h2>

<h2 id="final-result" name="final-result">
  :clipboard: Resultado final
</h2>

### [Clique aqui para ver o projeto rodando na Vercel](https://south-frontend-challenge.vercel.app/)

### Desktop preview
<div>
  <strong>Home</strong> <br>
  <img width="850" src="screenshots/desktop/home.png" />
  <hr>
  
  <strong>Shimmer effect</strong> <br>
  <img width="850" src="screenshots/desktop/shimmer.png" />
  <hr>
  
  <strong>Modal de detalhes</strong> <br>
  <img width="850" src="screenshots/desktop/modal.png" />
  <hr>
  
  <strong>Lista de quadrinhos</strong> <br>
  <img width="850" src="screenshots/desktop/comics-list.png" />
  <hr>
</div>

### Mobile preview
<div>
  <strong>Home</strong> <br>
  <img width="320" src="screenshots/mobile/home.png" />
  <hr>
  
  <strong>Shimmer effect</strong> <br>
  <img width="320" src="screenshots/mobile/shimmer.png" />
  <hr>
  
  <strong>Modal de detalhes</strong> <br>
  <img width="320" src="screenshots/mobile/modal.png" />
  <hr>
  
  <strong>Lista de quadrinhos</strong> <br>
  <img width="320" src="screenshots/mobile/comics-list.png" />
  <hr>
</div>

<h2 id="features" name="features">
  :clipboard: Funcionalidades
</h2>

- [x] App lista os quadrinhos ao carregar
- [x] Usu??rio pode procurar por quadrinhos
- [x] Usu??rio pode carregar mais quadrinhos (p??gina????o)
- [x] Efeito shimmer para o carregamento inicial
- [x] Usu??rio pode adicionar quadrinhos na sua lista
- [x] Usu??rio pode enviar um e-mail para algu??m com os quadrinhos da sua lista (com um link mailto, o ideal seria ter um back-end para isso, n??o pude desenvolver isso por falta de tempo)
- [x] Estilos responsivos
- [x] Usu??rio pode ver mais detalhes do quadrinho atrav??s de um modal

<h2 id="tests" name="tests">
  :test_tube: Testes
</h2>

Um resumo dos teste s??o:

- [x] Testes dos contextos de Modal e de Lista de Quadrinhos
- [x] Testes da p??gina Home
- [x] Testes da p??gina ComicsList / Lista de Quadrinhos
- [x] Testes do componente Header
- [x] Testes dos utils

<h3 align="center">100% de cobertura nos testes :heavy_check_mark:</h3>
<p align="center">
  <img width="750" src="screenshots/coverage.png" />
</p>

<h3 align="center">Testes com mais detalhes :heavy_check_mark:</h3>
<p align="center">
  <img width="750" src="screenshots/verbose.png" />
</p>

<h2 id="techonologies" name="technologies">
  :rocket: Tecnologias utilizadas
</h2>

- [Next.js](https://nextjs.org/)- Next.js ?? um framework front-end constru??do em cima do React, ele traz algumas funcionalidades prontas como sistema de rotas por arquivos, gera????o de p??ginas est??ticas e renderizadas no servidor. Eu o usei para desenvolver a app toda no geral.
- [TypeScript](https://www.typescriptlang.org/) - Typescript ?? um superset da linguagem JavaScript, usei ele para ganhar mais produtividade durante o desenvolvimento do projeto. Com ele, podemos tipar nossas vari??veis, fun????es, e afins, o que facilita manuten????o do c??digo.
- [Styled Components](https://styled-components.com/) - Styled components ?? uma biblioteca de CSS-in-JS, nela, escrevemos CSS como SCSS por??m dentro de arquivos JavaScript ou TypeScript, o que torna poss??vel deixar nossos estilos mais program??veis. Eu a utilizei para estilizar toda a app.
- [Axios](https://axios-http.com/) - Axios ?? uma biblioteca para requisi????es HTTP, eu a utilizei para consumir a API da Marvel.
- [React Testing Library](https://testing-library.com/) - React Testing Library ?? uma bibloteca que permite que possamos testar nossos componentes React de forma simples e r??pida. Eu a utilizei com [Jest](https://jestjs.io/pt-BR/), para assim poder testar as p??ginas, componentes e contextos.
- [API de Contexto do React](https://pt-br.reactjs.org/docs/context.html) - A API de contextos do React permite que possamos gerenciar o estado de nosso app de forma mais simples, ela resolve o famoso problema no universo front-end conhecido como [prop-drilling](https://www.alura.com.br/artigos/prop-drilling-no-react-js).
- [React Modal](https://github.com/reactjs/react-modal) - A React Modal ?? uma biblioteca para podermos utilizar Modais dentro de aplica????es front-end com React.
- [Sweet Alert](https://sweetalert2.github.io/) - Sweet Alert ?? uma biblioteca para poder mostrar mensagens de alerta e toasts. A utilizei para fazer os toasts quando o usu??rio adiciona ou remove um quadrinho da sua lista.
- [Faker](https://github.com/marak/Faker.js/) - Faker ?? uma biblioteca para poder gerar valores aleat??rios. Eu a utilizei para os testes automatizados.

<h2 id="deploy" name="deploy">
  :rocket: Deploy
</h2>

Eu fiz o deploy dessa aplica????o na [Vercel](https://vercel.com/). Ela est?? configurada com uma integra????o cont??nua (continuous integration) com este reposit??rio do Github, isso ??, toda vez que o c??digo do reposit??rio no Github na branch main tiver uma atualiza????o, a Vercel rodar?? o build do projeto e o colocar?? em produ????o.
[Clique aqui para ver o projeto em produ????o](https://south-frontend-challenge.vercel.app/)

<h2 id="how-to-run" name="how-to-run">
  :arrow_forward: Como rodar
</h2>

### Passos iniciais
Antes de tudo, voc?? precisar?? clonar o reposit??rio e instalar as depend??ncias. Assumindo que voc?? tenha [Yarn](https://yarnpkg.com/), siga os passos abaixo:
```
# Clone o reposit??rio
$ git clone https://github.com/TiagoDiass/south-frontend-challenge.git

# Entre no reposit??rio
$ cd south-frontend-challenge

# Instale as depend??ncias
$ yarn install
```

### Projeto
Para rodar o projeto, basta realizar os seguintes passos(assumindo que voc?? seguiu os passos iniciais)
```
# Inicie o app
$ yarn dev
```

### Testes
Para rodar os testes, basta realizar os seguintes passos(assumindo que voc?? seguiu os passos iniciais)
```
# Rode os testes
$ yarn test

# Caso queira rodar os testes de forma a ver a cobertura do c??digo, rode:
$ yarn test:coverage
```

:wave: Espero que voc?? tenha gostado deste projeto :smiley: <br>

### Author: [Tiago Dias](https://www.linkedin.com/in/tiagodiass)

