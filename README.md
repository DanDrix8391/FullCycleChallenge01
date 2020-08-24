# Desafio Full Cycle 4.0 - Hello World com Docker (em Python)

Comando para criar a imagem

```bash
$ docker build -t full-cycle-challenge01:latest .
```

Comando para rodar a Imagem

```bash
$ docker run -p 8080:8080 full-cycle-challenge01:latest
```

A aplicação vai estar disponível em http://localhost:8080 
