# DSCommerce

Projeto backend desenvolvido como desafio prático da formação
**Java Spring Professional — DevSuperior**.

O DSCommerce é uma API REST para um sistema de comércio eletrônico,
utilizada durante a formação para aplicar conceitos de desenvolvimento
backend com Java e Spring Boot.

> Este repositório representa um projeto de formação desenvolvido a partir
> das especificações e desafios propostos pela DevSuperior.

## Tecnologias

- Java 17
- Spring Boot 3.2
- Spring Web
- Spring Data JPA
- Hibernate
- Bean Validation
- Spring Security
- OAuth2
- H2 Database
- Maven
- JUnit
- Spring Security Test
- Postman

## Objetivos do projeto

O projeto foi utilizado para praticar conceitos importantes do
desenvolvimento de APIs com Spring Boot, incluindo:

- estruturação de uma aplicação Spring Boot;
- arquitetura em camadas;
- modelagem de domínio;
- persistência de dados com JPA/Hibernate;
- criação de endpoints REST;
- validação de dados;
- tratamento de erros e exceções;
- autenticação e autorização;
- segurança com Spring Security e OAuth2;
- testes automatizados.

## Estrutura

A aplicação segue uma organização em camadas, separando responsabilidades
entre os componentes da aplicação.

A estrutura inclui conceitos como:

- **Entities** — representação das entidades do domínio;
- **Repositories** — acesso e persistência dos dados;
- **Services** — regras e operações da aplicação;
- **Controllers/Resources** — exposição dos endpoints REST;
- **DTOs** — transferência de dados entre a API e seus clientes;
- **Config/Security** — configuração e segurança da aplicação.

## API REST

O projeto disponibiliza uma API REST para trabalhar com os recursos do
domínio do DSCommerce.

O repositório também contém uma coleção do **Postman**, permitindo testar
as operações disponibilizadas pela API.

Arquivo:

`DSCommerce Cap05.postman_collection.json`

Também está disponível o ambiente utilizado no Postman:

`DSCommerce env.postman_environment.json`

## Banco de dados

O projeto utiliza **Spring Data JPA / Hibernate** para persistência e
**H2 Database** como banco de dados em memória no ambiente do projeto.

## Segurança

A aplicação utiliza **Spring Security** e componentes OAuth2 do ecossistema
Spring para autenticação e autorização dos recursos protegidos da API.

## Executando o projeto

### Pré-requisitos

- Java 17+
- Maven

Clone o repositório:

git clone https://github.com/gilcecler/dscommerce.git

Entre no diretório:

cd dscommerce

Execute:

./mvnw spring-boot:run

No Windows:

mvnw.cmd spring-boot:run

## Testes

O projeto possui estrutura de testes automatizados utilizando o suporte de
testes do Spring Boot e Spring Security.

Para executar:

./mvnw test

## Desafio original

As especificações utilizadas no desenvolvimento estão preservadas neste
repositório:

`05_DESAFIO_Projeto_Spring_estruturado.pdf`

Isso permite consultar os requisitos originais e comparar com a
implementação realizada.

## Contexto de formação

Este projeto faz parte da formação **Java Spring Professional**, da
**DevSuperior**, e representa um dos desafios práticos realizados durante
meus estudos de desenvolvimento backend com Java e Spring.

A formação abordou temas como:

- Java e orientação a objetos;
- modelagem de domínio;
- Spring Boot;
- APIs REST;
- JPA/Hibernate;
- SQL e JPQL;
- validação;
- tratamento de exceções;
- Spring Security;
- OAuth2 e JWT;
- testes automatizados.

## Autor

**Gilcecler Carneiro**

Desenvolvedor Java/Spring Boot e Analista de Sistemas.

GitHub: https://github.com/gilcecler
