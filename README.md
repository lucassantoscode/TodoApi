# To-Do List API

![C#](https://img.shields.io/badge/C%23-.NET%20Core-green) ![License](https://img.shields.io/badge/License-MIT-lightgrey)

API simples de gerenciamento de tarefas (To-Do), construída em **C# / ASP.NET Core**, para estudo e aprendizado de APIs REST.

---

## 🔹 Tecnologias

- **C# / ASP.NET Core**: Backend API
- **Visual Studio / VS Code**: Desenvolvimento
- **.NET 7 (ou 8)**: Plataforma

---

## 📂 Estrutura do Projeto
```
TodoApi/
├─ Controllers/
│ └─ TodoController.cs
├─ Data/
│ └─ TodoContext.cs
├─ Models/
│ └─ TodoItem.cs
├─ Program.cs
├─ TodoApi.csproj
├─ README.md
└─.gitignore
```
---

## ⚡ Como Rodar

1. Abra o terminal na pasta do projeto:

```bash
cd TodoApi
```
2. Execute a API:

```bash
dotnet run
```
-  A API estará rodando em http://localhost:5000 (ou HTTPS em 5001).

🌐 Endpoints
```
Método	Endpoint	    Descrição
GET	    /todo	    Lista todas as tarefas
GET	    /todo/{id}	Busca tarefa por ID
POST	/todo	    Cria nova tarefa
PUT	    /todo/{id}	Atualiza tarefa existente
DELETE	/todo/{id}	Deleta tarefa por ID
```
-  Os dados são enviados/recebidos em JSON.

📌 Observações

-  Projeto feito para estudo e aprendizado.
-  Pode ser expandido para banco de dados real, autenticação, ou front-end.
