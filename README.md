## Sobre
Aplicação web para cadastro de produtos, o qual utiliza as tecnologias de desenvolvimento: Java, Spring Boot, Lombok, MySQL, React.<br><br>

## Configurando o projeto no VS Code

### [Backend]
#### 1. Baixar extensões
+ Java Extension Pack
+ Spring Boot Extension Pack
+ Thunder Client
  
#### 2. Criar um projeto Spring Boot no VS Code
1. Abrir seletor de comandos (Ctrl+Shift+P)
2. Selecionar "Spring Initializr: Create a Maven Project"
3. Terminar de configurar o projeto

#### 3. Clonar o arquivo pom.xml / adicionar as dependências
* mysql-connector-java
* spring-boot-devtools
* spring-boot-starter-web
* spring-boot-starter-data-jpa
* lombok

#### 4. Editar o arquivo resources/application.properties

Altera a estrutura da tabela caso a entidade tenha mudanças <br>
`spring.jpa.hibernate.ddl-auto=update`

Acesso ao banco de dados <br>
`spring.datasource.url=jdbc:mysql://${MYSQL_HOST:localhost}:3306/api_spring`

Usuário do banco de dados <br>
`spring.datasource.username=root`

Senha do banco de dados <br>
`spring.datasource.password=`
