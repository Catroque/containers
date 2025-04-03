## PostgreSQL

```bash
# baixando a imagem
docker pull postgres:17.4
```

```bash
# executando em background usuário "postgres" senha "postgres"
docker run -itd --name postgres -p 5432:5432 -e POSTGRES_PASSWORD=postgres -d postgres:17.4
```

