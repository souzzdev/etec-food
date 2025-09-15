# Projeto Delivery System

![Delivery Banner](https://img.icons8.com/ios-filled/100/000000/delivery--v1.png)

---

## 📋 Sobre o Projeto

Este projeto é um sistema de delivery que gerencia clientes, pedidos, entregas e entregadores, visando otimizar o processo de entrega e o relacionamento com os clientes. O modelo relacional foi baseado em entidades como **Cliente**, **Pedido**, **Entrega**, **Entregador**, **Restaurante** e seus relacionamentos, conforme diagrama UML desenvolvido.

---

## 🚀 Tecnologias Utilizadas

| Tecnologia         | Descrição                                   |
|--------------------|---------------------------------------------|
| **Java 17**        | Linguagem principal do projeto               |
| **Spring Boot 3.x**| Framework para desenvolvimento backend      |
| **Spring Web**     | Construção de APIs RESTful                    |
| **Spring Data JPA**| Integração com banco de dados via JPA/Hibernate |
| **Lombok**         | Redução de código boilerplate (getters, setters) |
| **Banco de Dados** | SQL Server / MySQL (dependendo do ambiente)  |

---

## 📦 Dependências Principais

- **spring-boot-starter-web**: Suporte para criação de aplicações web e APIs REST.
- **spring-boot-starter-data-jpa**: Suporte para JPA, facilitando o acesso a dados relacionais.
- **lombok**: Biblioteca para reduzir código repetitivo, como getters, setters, construtores.
- **driver JDBC**: Para conexão com o banco de dados (SQL Server ou MySQL).

---

## 🛠️ Funcionalidades Principais

- Cadastro e validação de **Clientes**
- Registro de **Pedidos** vinculados a restaurantes e clientes
- Controle de **Entregas**, associando pedidos e entregadores
- Gerenciamento dos **Entregadores** e status das entregas
- Mapeamento relacional completo conforme diagrama UML

---

## 🔧 Configurações importantes

Configure o banco de dados no `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/cliente
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```
## 🚀 Como rodar o projeto

1. Faça o fork do repositório original  1. Faça o fork do repositório original
2. Clone seu fork localmente:
   git clone https://github.com/seu-usuario/seu-fork.git
3. Crie e trabalhe nas suas branches de funcionalidade
4. Faça commits e pushes para suas branches específicas:
  git push origin sua-branch
5. Ao final do desenvolvimento, abra um Pull Request para o repositório original, que fará o merge das branches

🤝 Fluxo de contribuição via fork

Cada desenvolvedor cria sua branch para trabalhar em uma funcionalidade

Após concluir, envia um Pull Request para revisão

Todas as branches serão mescladas (merge) na branch principal (main) do projeto original

📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para detalhes.
