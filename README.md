
Primeiramente você deve rodar o comando npm i vue-router@4 <br>
  Feito isso você deve alterar a linha de código do seu main.js para:
  
    import { createApp } from "vue";
    import App from "./App.vue";
    import router from "./router";

    import "@/assets/base.css";

    const app = createApp(App);

    app.use(router);

    app.mount("#app");


(caso esteja usando outro nome de folha de estilo css apenas altere de "base.css" para o "nome-do-seu-arquivo.css")

  Feito isso você deve baixar ou recriar os arquivos que estão disponibilizados nesse repositório dentro do seu projeto, os arquivos são:
  
 // A pasta router com o arquivo index.js dentro. <br>
 // A pasta views com o arquivo TemplateComponente.vue (a pasta views é o lugar onde os seus componentes de pagina raiz irão ficar).
 
Dentro App.vue importar o routerview com o código:
  import {RouterView } from "vue-router";
  
