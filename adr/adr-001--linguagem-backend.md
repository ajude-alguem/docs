# ADR-001 - Linguagem de Backend

## Status
Accepted

## Context
Necessitamos escolher uma linguagem de backend capaz de suportar altas cargas de dados, e tráfego de usuários orgânico, assim como facilidade e pouca verbosidade para desenvolvimento técnico. Além disso, é necessário que se escolha uma linguagem sem necessidade de licenciamento, e preferêncialmente com comunidade de desenvolvedores grande e ativa.

## Decision
Decidimos pelo uso de Javascript com Node.JS, já que é uma linguagem com grande comunidade de desenvolvedores, não precisa de licenciamento, e por ter uma curva de aprendizado suave. Para facilitar ainda mais e aumentar a produtividade, decidimos por não trabalhar neste momento com TypeScript, ou seja, trabalhar somente com JavaScript puro.

## Consequences
Por ter escolhido não trabalhar com TypeScript, pode ser que no futuro essa decisão tenha que ser revista, para casos em que uma estrutura de dados mais complexa venha a ser necessária, trazendo a necessidade de trabalho com linguagem fortemente tipada.