
Sistema de gerenciamentos de pessoas em API REST com Spring Boot e deploy no Heroku

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```
## API



| URL | Método | Descrição |
|-----|--------|-----------|
 | /people| GET | informações de todas pessoas do sistema|
| /people/{id} | GET | informações específicas de uma pessoa |
|/people| POST| Cria uma nova entidade pessoa|
|/people/{id}| PUT | modifica uma pessoa |
|/people/{id}| DELETE | deleta uma pessoa|

