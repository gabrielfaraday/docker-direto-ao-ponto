# Examplo com .NET

Rode os seguintes comandos:

```shell

    docker build . -t docker-dap-dotnet

    docker run -d -p 5000:80 docker-dap-dotnet

```

E acesse no seu browser: http://localhost:5000/weatherforecast


## Exemplo com variavel de ambiente

Rode os seguintes comandos:

```shell

    docker stop [CONTAINER_ID]

    docker run -d -p 5000:80 -e DOTNET_ENVIRONMENT=Development docker-dap-dotnet

```

E acesse no seu browser: http://localhost:5000/swagger

