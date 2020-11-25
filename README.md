# vue-flask-crud

Pequena aplicação single page, feita em VUE e utilizando Flask como API.

Trata-se de uma lista de livros, com um CRUD básico.

Desenvolvido seguindo [este](https://testdriven.io/blog/developing-a-single-page-app-with-flask-and-vuejs/) tutorial, para fins de estudo.

## Desenvolvimento

- Client criado usando o VUE Cli:

```
npm install -g @vue/cli
vue create client
```

- Opções selecionadas:

```
Vue CLI v3.7.0
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, Router, Linter
? Use history mode for router? Yes
? Pick a linter / formatter config: Airbnb
? Pick additional lint features: Lint on save
? Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? In package.json
? Save this as a preset for future projects? (y/N) No
```

- Dependências adicionais:
  - `axios`: para enviar requisições AJAX
  - `bootstrap`: para deixar bunito
  - `bootstrap-vue`: Pois as modais usam Jquery, e deve-se **evitar** usar Jquery e Vue juntos. Pois Vue utiliza o *Virtual Dom* para manipular o DOM, enquanto que o Jquery não.

```
npm install axios --save
npm install bootstrap --save
npm install bootstrap-vue --save
```

