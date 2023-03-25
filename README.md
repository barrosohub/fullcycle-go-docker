# Projeto Full Cycle com Go e Docker

Este projeto é um exemplo simples de como criar uma aplicação Go e empacotá-la em uma imagem Docker. Quando executada, a aplicação imprime "Full Cycle Rocks!!" no console.

## Como rodar e testar o projeto

1. Clone este repositório:
```bash
git clone https://github.com/barrosohub/fullcycle-go-docker.git
cd fullcycle-go-docker
```

2. Construa a imagem Docker:
```bash
docker build -t barrosofilho/fullcycle .
```

3. Execute a imagem Docker:
```bash
docker run barrosofilho/fullcycle
```

Você verá a mensagem "Full Cycle Rocks!!" como resultado.