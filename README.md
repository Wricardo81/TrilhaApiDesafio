# 📌 Gerenciador de Tarefas - API com .NET e Entity Framework

![Swagger UI](https://raw.githubusercontent.com/Wricardo81/TrilhaApiDesafio/main/.github/images/swagger-preview.png)

[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/Wricardo81/TrilhaApiDesafio/actions)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#)

Este é um projeto desenvolvido como parte do desafio da [Trilha .NET da DIO](https://www.dio.me), utilizando ASP.NET Core Web API com Entity Framework Core. O objetivo é construir 
um sistema CRUD para gerenciamento de tarefas com integração ao Swagger e banco de dados em memória.

---

## 🔧 Funcionalidades

- ✅ Criar uma nova tarefa
- ✅ Obter tarefa por ID
- ✅ Atualizar uma tarefa existente
- ✅ Remover tarefa
- ✅ Filtrar tarefas por:
  - Título
  - Data
  - Status
- ✅ Listar todas as tarefas

---

## 📁 Estrutura da Tarefa

```json
{
  "id": 0,
  "titulo": "string",
  "descricao": "string",
  "data": "2022-06-08T01:31:07.056Z",
  "status": "Pendente"
}

🔗 Endpoints

| Verbo    | Rota                     | Parâmetros       | Corpo       |
| -------- | ------------------------ | ---------------- | ----------- |
| `GET`    | `/Tarefa/{id}`           | `id`             | N/D         |
| `GET`    | `/Tarefa/ObterTodos`     | -                | N/D         |
| `GET`    | `/Tarefa/ObterPorTitulo` | `titulo` (query) | N/D         |
| `GET`    | `/Tarefa/ObterPorData`   | `data` (query)   | N/D         |
| `GET`    | `/Tarefa/ObterPorStatus` | `status` (query) | N/D         |
| `POST`   | `/Tarefa`                | -                | JSON Tarefa |
| `PUT`    | `/Tarefa/{id}`           | `id`             | JSON Tarefa |
| `DELETE` | `/Tarefa/{id}`           | `id`             | N/D         |


🚀 Como executar localmente
Pré-requisitos
.NET 6 SDK

Editor de código como VS Code

Passos
# Clonar o repositório
git clone https://github.com/Wricardo81/TrilhaApiDesafio.git
cd TrilhaApiDesafio

# Restaurar pacotes
dotnet restore

# Executar a aplicação
dotnet run


🧪 Tecnologias Utilizadas
ASP.NET Core 6 Web API
Entity Framework Core (InMemory)
Swagger UI
LINQ
C#

👤 Autor
Ricardo Santos
GitHub: @Wricardo81
