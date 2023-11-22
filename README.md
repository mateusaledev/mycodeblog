--------------------------------------------------------------------------------------------
# MyCodeBlog

O MyCodeBlog é um projeto de blog desenvolvido em Spring Boot, que permite aos usuários publicar e visualizar posts relacionados a programação e tecnologia.

## Configuração do Ambiente

### Pré-requisitos

Certifique-se de ter o seguinte instalado em seu ambiente de desenvolvimento:

- Java 8 ou superior
- Maven
- PostgreSQL

### Configuração do Banco de Dados

O projeto utiliza o PostgreSQL como banco de dados. Certifique-se de criar um banco de dados chamado `codeblog` com as configurações apropriadas. As configurações de conexão podem ser ajustadas no arquivo `application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/codeblog
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
```

## Executando o Projeto

Clone o repositório para o seu ambiente local e execute o seguinte comando:

```bash
mvn spring-boot:run
```

O projeto estará acessível em [http://localhost:8080](http://localhost:8080).

## Funcionalidades Principais

- **Visualização de Posts:** Acesse a página de posts em [http://localhost:8080/posts](http://localhost:8080/posts) para ver os posts existentes.

- **Detalhes do Post:** Clique em um post para ver seus detalhes em [http://localhost:8080/posts/{id}](http://localhost:8080/posts/{id}).

- **Adição de Novo Post:** Crie um novo post em [http://localhost:8080/newpost](http://localhost:8080/newpost).

## Conta de Administração

Para fins de demonstração, uma conta de administrador está configurada:

- **Usuário:** deadpool
- **Senha:** 123

## Contribuição

Sinta-se à vontade para contribuir para o projeto! Se encontrar problemas ou tiver sugestões, abra uma [issue](https://github.com/seu-usuario/mycodeblog/issues) ou envie um [pull request](https://github.com/seu-usuario/mycodeblog/pulls).

---