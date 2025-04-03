## PostgreSQL

```bash
# baixando a imagem
docker pull postgres:17.4
```

```bash
# executando em background usuário "postgres" senha "postgres"
docker run -itd --name postgres_general -e POSTGRES_PASSWORD=postgres -d postgres:17.4
```

