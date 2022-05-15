# ADR-002 - Linguagem e Framework de Frontend

## Status
Accepted

## Context
Necessitamos escolher uma linguagem e framework de Frontend capaz de suportar regras de negócio complexas. Linguagem e framework não podem ser licenciados. Framework precisa suportar trabalho com módulos e componentes para facilitar reutilização de código entre diferentes sistemas web. Linguagem precisa ter grande comunidade de desenvolvedores.

## Decision
Decidimos pelo uso de Javascript com React.JS, já que é uma linguagem com grande comunidade de desenvolvedores, não precisa de licenciamento. Para facilitar e aumentar a produtividade, decidimos por não trabalhar neste momento com TypeScript, ou seja, trabalhar somente com JavaScript puro.

## Consequences
Por ter escolhido não trabalhar com TypeScript, pode ser que no futuro essa decisão tenha que ser revista, para casos em que uma estrutura de dados mais complexa venha a ser necessária, trazendo a necessidade de trabalho com linguagem fortemente tipada.