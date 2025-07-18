# 📝 TodoApi em 20 minutos com .Net

API REST para gerenciamento de tarefas (Todos) construída com ASP.NET Core, Entity Framework Core e SQLite.


## 📂 Estrutura do Projeto

```
TodoApi/
├── Controllers/
├── Data/
├── Models/
├── Program.cs
├── appsettings.json
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

## 🚀 Como executar

### Com Docker

1. **Build e execução**
   ```bash
   docker-compose up --build
   ```
2. **Acesse a API**
   - Swagger: [http://localhost:8080/swagger](http://localhost:8080/swagger)

### Sem Docker

1. **Restaurar dependências**
   ```bash
   dotnet restore
   ```
2. **Executar a aplicação**
   ```bash
   dotnet run
   ```
3. **Acesse a API**
   - Swagger: normalmente em [http://localhost:5125/swagger](http://localhost:5125/swagger) ou [http://localhost:5000/swagger](http://localhost:5000/swagger)

---

## 🛠️ Tecnologias

- ASP.NET Core 8
- Entity Framework Core
- SQLite
- Docker

---
## 👨‍💻 Autor

<a href="https://github.com/jusansilva">
 <img style="border-radius: 50%;" src="https://github.com/jusansilva.png" width="100px;" alt="Foto de Jusan Magno"/>
 <br />
 <sub><b>Jusan Magno</b></sub>
</a>
<br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jusanmagno/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jusansilva)
---


