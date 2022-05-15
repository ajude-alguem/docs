# ADR-003 - Arquitetura Cloud 

## Status
Accepted

## Context
Necessitamos escolher um sistema de computação em nuvem padrão para toda a infraestrutura da plataforma Ajude Alguém. Temos a necessidade de, a priori, termos baixos custos (de preferência custos zero), e facilidade para "go-live", ou seja, colocar SPAs, microsserviços e bancos de dados no ar sem muita, ou nenhuma, dificuldade ou esforço técnico. Também deve-se considerar um sistema de cloud seguro, robusto e maduro em termos de segurança.

## Decision
Nessa ADR nossa decisão foi pelo uso da plataforma HEROKU, que provê soluções de computação em núvem de fácil setup, e custo zero nesse primeiro momento. Heroku permite configurações de SPAs e microsserviços com certa facilidade, suportando aplicações NODE.js e REACT.js, conforme (ADR-001 - Linguagem de Backend)[adr-001--linguagem-backend.md] e (ADR-002 - Linguagem e Framework de Frontend)[adr-002--linguagem-framework-frontend.md].

## Consequences
Como conseguência dessa decisão, não teremos profundidade e controle de baixo nível nas configurações de infraestrutura, porém ganhamos com pipelines pré-configurados para já iniciar o projeto com implantação via CI/CD.