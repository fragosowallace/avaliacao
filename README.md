# Controle de Transações de Crédito em Conta com Cartão

## Visão Geral

Este projeto implementa um sistema de controle de transações de crédito em conta com cartão. 
Ele permite que cada portador de cartão (cliente) tenha uma conta com seus próprios dados e realize operações que geram transações associadas à sua conta. 
Cada transação possui um tipo (compra à vista, compra parcelada, saque ou pagamento), um valor e uma data de criação.

## Tecnologias

- Spring Boot 2.7: Framework Java para desenvolvimento de aplicativos web.
- MySQL: Sistema de gerenciamento de banco de dados relacional.
- Java 1.8: Linguagem de programação.
- Outras bibliotecas e tecnologias relevantes.

## Configuração

### Banco de Dados MySQL

Certifique-se de ter um servidor MySQL em execução e configure as seguintes informações no arquivo `application.properties` do Spring Boot:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/avpactomais
spring.datasource.username=root
spring.datasource.password=
