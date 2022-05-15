# ADR-004 - Micro Serviços

## Status
Accepted

## Context
Precisamos decidir entre o uso de arquitetura monolítica ou micro-serviços, considerando que é esperado que essa plataforma seja expandida em termos de tráfego e funcionalidades com o passar do tempo.

## Decision
Nossa decisão foi seguir o melhor padrão de mercado de micro-serviços para desenvolvimento do backend da plataforma Ajude Alguém. Decidimos por usar micro-serviços a fim de que a infra-estrutura de computação do backend seja escalável de forma segregada. Também foi um fator de decisão que no longo prazo devemos ter uma equipe cada vez maior de desenvolvedores, e trabalhar com sistemas sub-divididos facilita na gestão de projetos e gestão técnica.

## Consequences
Como consequência dessa decisão, fica a cargo da infra-estrutura abstrair toda a complexidade de comunicação entre os micro-serviços, complexidade essa que estaria embarcada numa solução monolítica, que foi descartada.