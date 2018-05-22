# react-academind
Curso de React do canal Academind

## Sobre
Biblioteca baseada em JavaScript para criar interfaces interativas para o usuário.

### Declarativa
É possível criar views com um design simples com estados diferentes para sua aplicação, com o Reac atualizando e renderizando os componentes quando a informação for alterada/atualizada.

Views declarativas são mais fáceis de debugar e deixar seu código mais previsivel.

### Baseada em componentes 
A construção encapsulada de componentes é o que gerenciam seu próprio estado e em seguida o compõe para criar interfaces.

Como a lógica do componente é escrita em JavaScript em vez de models, você pode facilmente passar dados por meio do seu aplicativo e manter o estado fora do DOM.

## Angular x React
* Angular

Usado para criar single page applications, seu servidor envia apenas uma view.

* React

React pode criar views (SPA) ou partes de uma view. Single components ou widgets no qual é consumido pela view.

## O que é necessário para o React
Utilizar 2 JavaScript diferentes para cuidar da renderização.

Webpack controla todos os assets (imagens, css, sass).

---

## Instalação
Necessário ter node instalado na última versão estável.

Para iniciar a aplicação digite o comando abaixo e preencha as informações necessárias.
```js
npm init
```

Para instalar react e o react dom para manipular o dom da aplicação. O *--save* é para salvar as dependências no *package.json*
```js
npm install react react-dom --save
```

Para instalar o webpack e o servidor dev para webpack.
```js
npm install webpack webpack-dev-server
```