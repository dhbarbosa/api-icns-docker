# Configuraçao do Docker | ICNS-API | Fatec de Cotia 2023

## Infomações

A Criação do nosso projeto tem como intuito o aprendizado e desenvolvimento de um API feita em Java/Spring, ultizando ferramentas/bibliotecas como Docker, JWT, Bcrypt, Postgresql e outros.

### Ambiente
  PG Admin
  Docker
  
### Modo de Exec.

-   Clonando o repositorio.

```bash
git clone https://github.com/diogoHenBarbosa/api-icns-docker docker-api
```

-   Indo para o diretorio.

```bash
cd docker-api
```

-   Configure as váriaveis de ámbiente.

```bash
cd config
```

-   Altere e renomei o arquivo api.env.exemplo para api.env.

```bash
  POSTGRES_USER= 
  POSTGRES_DB= 
  POSTGRES_PASSWORD= 
  API_SECRET= 
  API_ISSUER= 
  PORT=5432
  PORT_SERVER= 8080
  IP_BD=172.16.0.2
```

-   Na pasta principal, suba as máquinas

```bash
docker-compose up

```
