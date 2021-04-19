# Ambiente de desenvolvimento PHP com Docker Compose

Através do Docker Compose, cria um ambiente virtual php com mysql.

## Instalação

- Criar máquina virtual:
```
docker-compose up

```

- Iniciar máquina virtual:

```
docker-compose start

```

- Parar máquina virtual:

```
docker-compose stop

```

Obs: Se caso for utilizar Windows:
- Instale o projeto na pasta Users
- Utilize winpty se quiser acessar um container específico. Ex: winpty docker exec -it php_php_1 bash

## Pré requisitos
- Docker 
- Docker Compose