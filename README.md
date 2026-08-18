# Workshop Spring

API REST desenvolvida com **Java e Spring Boot**, com foco em desenvolvimento backend, persistência de dados utilizando **JPA/Hibernate**, integração com banco de dados relacional e organização em camadas.

Este projeto foi desenvolvido durante meus estudos de **Java Backend** e tem como objetivo aplicar, na prática, conceitos do ecossistema Spring e de desenvolvimento de APIs REST.

## 🚀 Tecnologias utilizadas

* **Java 21**
* **Spring Boot 4.1.0**
* **Spring Web MVC**
* **Spring Data JPA**
* **Hibernate**
* **PostgreSQL**
* **H2 Database**
* **Maven**
* **Git & GitHub**

## 📌 Sobre o projeto

O projeto consiste em uma aplicação backend desenvolvida utilizando Spring Boot, seguindo uma arquitetura organizada em diferentes camadas.

Durante o desenvolvimento, foram aplicados conceitos importantes de desenvolvimento backend, como:

* Desenvolvimento de APIs REST;
* Programação Orientada a Objetos;
* Injeção de Dependências;
* Arquitetura em camadas;
* Mapeamento de entidades com JPA;
* Persistência de dados;
* Spring Data JPA;
* Hibernate;
* Integração com PostgreSQL;
* Utilização do H2 para ambiente de desenvolvimento/testes.

O principal objetivo do projeto é consolidar os fundamentos do **Spring Boot, JPA/Hibernate e desenvolvimento de APIs REST** por meio de uma aplicação prática.

## 🏗️ Estrutura do projeto

O projeto está organizado seguindo uma separação de responsabilidades:

```text
src
└── main
    ├── java
    │   └── com.web.workshop
    │       ├── config
    │       ├── entities
    │       ├── repositories
    │       ├── resources
    │       ├── services
    │       └── WorkshopApplication.java
    │
    └── resources
        ├── application.properties
        ├── application-dev.properties
        └── application-test.properties
```

### Principais camadas

**Entities**

Responsáveis por representar as entidades do domínio e realizar o mapeamento entre objetos Java e tabelas do banco de dados utilizando JPA.

**Repositories**

Responsáveis pelo acesso e persistência dos dados através do Spring Data JPA.

**Services**

Responsáveis pela lógica de negócio e pela comunicação entre os controllers e repositories.

**Resources**

Contêm os endpoints REST responsáveis por receber as requisições HTTP e retornar as respostas da API.

**Config**

Contém configurações da aplicação e inicialização de dados.

## 🔄 Arquitetura

A aplicação utiliza uma arquitetura em camadas:

```text
Requisição HTTP
       ↓
Resource / Controller
       ↓
Service
       ↓
Repository
       ↓
Banco de Dados
```

Essa separação permite organizar melhor as responsabilidades da aplicação, facilitando sua manutenção e evolução.

## 🗄️ Banco de dados

O projeto utiliza **PostgreSQL** como banco de dados relacional.

Também foi configurado o **H2 Database**, que pode ser utilizado em ambientes de desenvolvimento e testes.

A persistência é realizada através de **JPA/Hibernate**, permitindo o mapeamento das entidades Java para as tabelas do banco de dados.

## ⚙️ Pré-requisitos

Para executar o projeto, é necessário ter instalado:

* Java 21 ou superior;
* Maven 3.9 ou superior;
* PostgreSQL, caso seja utilizado o ambiente com PostgreSQL.

Para verificar a versão do Java:

```bash
java -version
```

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/devchagas/workshop-spring.git
```

### 2. Acesse a pasta do projeto

```bash
cd workshop-spring
```

### 3. Execute a aplicação

No Linux/macOS:

```bash
./mvnw spring-boot:run
```

No Windows:

```bash
mvnw.cmd spring-boot:run
```

## 📡 API REST

A aplicação disponibiliza endpoints REST para gerenciamento dos recursos do sistema.

Os endpoints utilizam os principais métodos HTTP:

| Método   | Utilização         |
| -------- | ------------------ |
| `GET`    | Buscar recursos    |
| `POST`   | Criar recursos     |
| `PUT`    | Atualizar recursos |
| `DELETE` | Remover recursos   |

## 🧪 Testes

O projeto possui estrutura de testes utilizando o ecossistema de testes do Spring Boot.

Para executar os testes:

```bash
./mvnw test
```

No Windows:

```bash
mvnw.cmd test
```

## 📚 Conceitos praticados

Durante o desenvolvimento deste projeto, foram praticados conceitos como:

* Java;
* Programação Orientada a Objetos;
* Spring Boot;
* APIs REST;
* Injeção de Dependências;
* JPA;
* Hibernate;
* Spring Data JPA;
* Mapeamento objeto-relacional;
* Relacionamentos entre entidades;
* PostgreSQL;
* H2;
* Maven;
* Git e GitHub;
* Arquitetura em camadas.

## 🔮 Próximas melhorias

Algumas melhorias planejadas para futuras versões:

* [ ] Implementar DTOs para entrada e saída de dados;
* [ ] Melhorar o tratamento de exceções;
* [ ] Adicionar validações com Bean Validation;
* [ ] Aumentar a cobertura de testes automatizados;
* [ ] Adicionar documentação da API com OpenAPI/Swagger;
* [ ] Adicionar suporte ao Docker;
* [ ] Expandir o uso de paginação e ordenação.

## 👨‍💻 Autor

**Dev Chagas**

Estudante de **Engenharia de Software**, com foco em desenvolvimento **Java Backend**.

Atualmente estudando e desenvolvendo projetos utilizando:

* Java
* Spring Boot
* APIs REST
* SQL
* JPA/Hibernate
* PostgreSQL
* Git & GitHub

### 🔗 Repositório

[GitHub — workshop-spring](https://github.com/devchagas/workshop-spring)
