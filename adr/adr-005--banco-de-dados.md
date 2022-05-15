# ADR-005 - Banco de Dados

## Status
Accepted

## Context
Necessitamos de um banco de dados que suporte alto tráfego de leitura, e que seja simples e escalável. Conforme indicado no (ADR-004 - Micro-Serviços)[adr-004--microservicos.md], trabalharemos com microserviços, e precisamos de um banco de dados com estrutura simplificada, pois cada microserviço terá contexto de base e persistência reduzidos e coesos.

## Decision
Decidimos pelo uso de banco de dados não relacional, e especificamente escolhemos pela tecnologia MongoDB, hospedado no sistema Atlas. Conforme explicado na (ADR-003 - Arquitetura Cloud)[adr-003--arquitetura-cloud.md] trabalharemos com Heroku, que no momento atual, não suporta banco de dados MongoDB gratuitos. Por isso escolhemos hospedar a base no sistema Atlas.

## Consequences
A partir dessa decisão, fica a cargo das aplicações de micro-serviços que façam as devidas validações de carga de dados para garantir a integridade dos mesmos, já que trabalharemos com bancos não relacionais.