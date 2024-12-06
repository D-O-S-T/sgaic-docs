# Back-End

- **Framework**: Spring Boot 3.3.4
- **Versão**: Maven 4.0.0
- **Linguagem**: Java 21
- **Biblioteca** : Lombok [Download aqui](https://projectlombok.org/download)
- **Banco de Dados**: PostgreSQL 16.4
- **Ferramenta de Visualização**: DBeaver

# IDE Recomendada

- **IDE**: STS - Spring Tools Suite
- **Configuração do Lombok**:
    - Faça o download do arquivo Lombok: [Aqui](https://projectlombok.org/download) 
    - Associe o Lombok ao STS.

?> Dica: Certifique-se de que sua versão do STS suporta Java 21.

!> Alerta: Configurar adequadamente o Lombok é essencial para evitar erros na compilação.

# Dependências do Projeto

O projeto utiliza as seguintes dependências:

```xml
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-security</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.postgresql</groupId>
        <artifactId>postgresql</artifactId>
        <scope>runtime</scope>
    </dependency>
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <optional>true</optional>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>org.springframework.security</groupId>
        <artifactId>spring-security-test</artifactId>
        <scope>test</scope>
    </dependency>
</dependencies>
```

# Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:
   
 - **STS(Spring Tool Suite)**

 - **PostgreSQL com uma base de dados configurada.**

 - **Lombok, integrado ao STS.**

Além disso, tenha:

- O código-fonte do projeto localmente.
- O arquivo `application.yml` ou `application.properties` configurado para conexão com o PostgreSQL.

# Guia de Configuração do Projeto

