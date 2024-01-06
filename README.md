# Dio Desenvolvimento Frontend com Angular

Um blog simplificado, com algumas postagens do [Medium](https://medium.com/), a fim de praticar conceitos básicos no framework Angular.

# Conteúdo Dinâmico

Para simular o acesso dinâmico a um conteúdo por parte dos componentes, o conteúdo dos artigos foram agrupados em `articlesList.ts`, como um mock para um json retornado de uma API.

Os dados de um artigo específico são obtidos através do `ArticleService` que é injetado em todos os componentes que utilizarão esses dados.

`ArticleService`, portanto é a camada de abstração pela qual os componentes têm acesso às informações da mock API `articlesList`, funcionando como a camada _Model_ de uma arquitetura MVC.

