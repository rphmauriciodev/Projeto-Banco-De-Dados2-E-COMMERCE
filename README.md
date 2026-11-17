# Loja de Eletrônicos E-commerce – BD II (2ª Unidade), Etapa 1

Sistema OLTP com JPA 2.1 e Hibernate 5.2.10.Final sobre PostgreSQL, com console e API REST (Swagger UI).

## Como executar

Requer Docker (o Hibernate 5.2 exige JDK 8, que já vem na imagem).

```
docker compose up -d db
docker compose run --rm app carga
docker compose run --rm app console
docker compose up app
```

Swagger UI: http://localhost:8080/swagger

## Declaração de uso de IA

O Claude Code (Anthropic) foi utilizado neste projeto para:

- geração dos dados mockados (classe `CargaDados`: catálogo de produtos, clientes, lojas e pedidos);
- correção de bugs.
