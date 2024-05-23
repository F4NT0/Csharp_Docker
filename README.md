# Criando um projeto console com Docker

- Crie um projeto console usando o comando: `dotnet new console -o Project`
- Pode testar acessando o diretório Project e rodando: `dotnet run`
- Antes de por no Docker, publique as modificações: `dotnet publish -c Release`

- Para buildar a imagem do Dockerfile: `docker build -t projectCsharp .`
- Para iniciar um novo container: `docker run --name project-container projectCsharp`
- Para rodar o docker-compose: `docker-compose up --build`