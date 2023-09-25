# API Spring Boot CRM
Este é um exemplo de aplicativo Java/Maven/Spring Boot (versão 3.1.4) para cadastro, alteração, exclusão, listagem e consulta de clientes.

### Crie um recurso de Cliente

```
POST api/clientes
Accept: application/json
Content-Type: application/json

{
    "nome": "Edson Manoel Martins"
}

RESPONSE: HTTP 201 (Created)
Content: objeto recurso cliente
```

### Recuperar uma lista de Clientes

```
GET api/clientes

Response: HTTP 200
Content: lista
```

### Recuperar uma lista de Clientes

```
GET api/clientes

Response: HTTP 200
Content: lista
```

### Recuperar uma cliente específico

```
GET api/clientes/{id}

Response: HTTP 200
Content: objeto recurso cliente
```

### Deletar uma cliente específico

```
DELETE api/clientes
Accept: application/json
Content-Type: application/json

{
    "id": 1,
    "nome": "Edson Manoel Martins"
}

Response: HTTP 200
```

### Alterar um Cliente

```
PUT api/clientes
Accept: application/json
Content-Type: application/json

{
    "id": 1,
    "nome": "Edson Manoel Martins Souza"
}

Response: HTTP 200
Content: objeto recurso cliente
```
