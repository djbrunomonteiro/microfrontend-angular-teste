
# Microfrontend com projetos em versões de angular 16 - 15 e 14

Repositório de teste para avaliar microfrontend com @angular-architects/module-federation

Documentação: https://www.angulararchitects.io/en/blog/the-microfrontend-revolution-module-federation-in-webpack-5/

##### Para Executar:

* clone:
```http
 https://github.com/djbrunomonteiro/microfrontend-angular-teste.git
```

* Abra as pastas:

 /enuves-core   /enuves-eventos  /enuves-igrejas /enuves-relatorios

* Instale as depedências npm em cada projeto

```http
npm install
```

após é só servir ambos os projetos

```http
ng serve
```

Acesse o microfrontend via http://localhost:4200


// caso acesse algum microfrontend diretamente na sua porta (ex: http://localhost:4201)" ocorrerá um erro, pois os modules core do angular não será carregado.