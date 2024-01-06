# Dio Desenvolvimento Frontend com Angular

Este é um projeto simplificado para desenvolvimento frontend com Angular, criado durante a participação no curso do Dio. O objetivo é praticar conceitos básicos do framework, inspirando-se no formato de blog do [Medium](https://medium.com/).

## Conteúdo Dinâmico

Para simular o acesso dinâmico aos componentes, agrupei o conteúdo dos artigos no arquivo `articlesList.ts`, funcionando como um mock de JSON que poderia ser retornado por uma API.

A obtenção dos dados de um artigo específico é realizada através do `ArticleService`, que é injetado nos componentes responsáveis por exibir essas informações.

Dessa forma, o `ArticleService` atua como a camada de abstração, permitindo que os componentes acessem as informações da mock API `articlesList`. Ele desempenha o papel da camada _Model_ em uma arquitetura MVC.
