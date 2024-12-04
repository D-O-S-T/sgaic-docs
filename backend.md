# Back End
- **Framework**: 3.3.4 (Spring Boot)
- **Versão**: 4.0.0 (Maven)
- **Linguagem**: Java 21
- Lombok : https://projectlombok.org/download
- PostgreSQL 16.4
- Dbeaver para visualização do banco

## IDE Recomendada
- **IDE**: STS - Spring Tools Suite
- **Lombok**: Para utilizar Lombok no STS baixe o Lombok e adicione o STS. Link: https://projectlombok.org/download

?> Exemplo de texto informativo

!> Exemplo de texto de alarme

## Instalação dos Plugins
- PostgreSQL [TO-DO: como baixar]
- Lombok  [TO-DO: como baixar]
- Postman  [TO-DO: como baixar]

## Dependências do Projeto
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
