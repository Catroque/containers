## N8n

```bash
# criar um volume para armazenamento dos dados da ferramenta
docker volume create n8n_data
```

```bash
# baixar última imagem
docker pull docker.n8n.io/n8nio/n8n
```

```bash
# executar em background
docker run -itd --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```
