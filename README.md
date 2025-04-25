# Gestão de Resíduos - API

Este projeto é uma API desenvolvida em .NET para gerenciamento de resíduos, containerizada com Docker e equipada com um pipeline de CI/CD.

## Tecnologias Utilizadas

- ASP.NET Core (.NET 8)
- Docker
- Docker Compose
- GitHub Actions (CI/CD)

## Como executar localmente

Pré-requisitos:
- Docker
- Docker Compose

Passo a passo:
1. Abra o terminal (ou prompt de comando)
2. Vá até a pasta do projeto
3. Execute o comando:
   docker-compose up --build

A aplicação estará em: http://localhost:5000

## CI/CD com GitHub Actions

- CI/CD roda automaticamente ao subir código para o GitHub
- Usa Docker para criar e enviar imagens
- Deploy simulado para "staging" e "produção"
