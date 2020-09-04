# Projeto eShop - Implementação da arquitetura de micros serviços em .NET Core.
 
 ### Tecnologias Utilizadas
 * RabbitMQ para comunicação entre serviços.
 * Ocelot API Gateway
 * MediatR - Biblioteca com implementação do Mediator Pattern
 * Docker e docker-compose
 * MSSQL
 * Redis
 * MongoDB
 
 ## Como rodar o projeto com docker-compose
 1. Configure os arquivos docker-compose.yml e docker-compose.override.yml (Opcional)
 2. No diretório raiz do projeto `docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d` ou `docker-compose -f docker-compose.yml -f docker-compose.override.yml up --build`.
