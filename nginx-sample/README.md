# Examplo com NGINX

Rode os seguintes comandos:

```shell

    docker build . -t docker-dap

    docker run -d -p 8081:80 docker-dap

```

E acesse no seu browser: http://localhost:8081/