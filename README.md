# Spring Boot 3 - AP RESTFul Completa 

Fonte de estudo : Youtube - Spring Boot 3 | Curso Completo 2023 (Michelli Brito)  
Link do Vídeo : [youtube](https://www.youtube.com/watch?v=wlYvA2b1BWI)

### Endpoints consultáveis

##### Salvar novo produto
Verbo : POST  
URI: [localhost:8080/products](localhost:8080/products)  
JSON Body: 

```
{
    "name": "Lavadora LG",
    "value": 1500.00
}
```

##### Negar Salvar Novo Produto
Verbo : POST  
URI: [localhost:8080/products](localhost:8080/products)  
JSON Body: 

```
{
    "name": "",
    "value": 1500.00
}
```

##### Buscar Todos os Produtos
Verbo : GET  
URI: [localhost:8080/products](localhost:8080/products)  

##### Buscar Um Produto
Verbo : GET  
URI: [http://localhost:8080/products/f2873c32-5693-4de2-ad01-e645e4c94c48](http://localhost:8080/products/f2873c32-5693-4de2-ad01-e645e4c94c48)  

##### Atualizar Produto
Verbo: PUT  
URI: [http://localhost:8080/products/f4dfb322-4154-40e7-80bc-9c644b9a6649](http://localhost:8080/products/f4dfb322-4154-40e7-80bc-9c644b9a6649)  
JSON Body: 

```json
{
    "name": "Lavadora LG",
	"value": 2500.00
}
```

##### Excluir Produto
Verbo: DELETE  
URI: [http://localhost:8080/products/f4dfb322-4154-40e7-80bc-9c644b9a6649](http://localhost:8080/products/f4dfb322-4154-40e7-80bc-9c644b9a6649)  