
# 🚀 DotNet.MicroSaaS.CleanDDD.CQRS

Projeto base moderno e escalável para desenvolvimento de MicroSaaS em .NET 8, com foco em arquiteturas limpas, desacopladas e resilientes.

---

## 📦 Tecnologias e Arquitetura Utilizadas

- ✅ Clean Architecture  
- ✅ Domain-Driven Design (DDD)  
- ✅ CQRS com MediatR  
- ✅ Event Sourcing  
- ✅ RabbitMQ + Outbox Pattern  
- ✅ Polly para resiliência (retry, fallback, circuit breaker)  
- ✅ Serilog + Seq para logging estruturado  
- ✅ Testes automatizados (xUnit, Moq, Stryker.NET)  
- ✅ Docker + Docker Compose  
- ✅ Pronto para CI/CD  

---

## 🗂 Estrutura de Projetos

```
src/
├── DotNet.MicroSaaS.CleanDDD.CQRS.API
├── DotNet.MicroSaaS.CleanDDD.CQRS.Application
├── DotNet.MicroSaaS.CleanDDD.CQRS.Domain
├── DotNet.MicroSaaS.CleanDDD.CQRS.Infrastructure
├── DotNet.MicroSaaS.CleanDDD.CQRS.Persistence
├── DotNet.MicroSaaS.CleanDDD.CQRS.Worker

tests/
├── DotNet.MicroSaaS.CleanDDD.CQRS.UnitTests
├── DotNet.MicroSaaS.CleanDDD.CQRS.IntegrationTests
├── DotNet.MicroSaaS.CleanDDD.CQRS.MutationTests
```

---

## 📊 Diagrama de Dependência

Abaixo está o diagrama visual das dependências entre os projetos da solução:

![Diagrama de Dependência](diagram.png)

---

## 🛠️ Como rodar

### Pré-requisitos
- .NET 8 SDK
- Docker
- Docker Compose

### Executar infraestrutura local
```bash
docker-compose up -d
```

### Rodar aplicação
```bash
cd src/DotNet.MicroSaaS.CleanDDD.CQRS.API
dotnet run
```

---

## 🧪 Executar os testes

```bash
dotnet test
```

Testes de mutação (requer Stryker.NET):

```bash
dotnet tool install -g dotnet-stryker
dotnet stryker
```

---

## 🌐 Endpoints úteis

- `/health` — Health Check  
- `/swagger` — Documentação interativa da API  

---

## 🤝 Contribuindo

1. Fork o repositório  
2. Crie sua branch: `git checkout -b feature/minha-feature`  
3. Commit: `git commit -m 'Adiciona nova feature'`  
4. Push: `git push origin feature/minha-feature`  
5. Crie um Pull Request  

---

## 🧑‍💻 Autor

**André Rodrigues Côrte**    
[LinkedIn](https://www.linkedin.com/in/andre-rodrigues-corte/)

---

## 📝 Licença

Distribuído sob licença MIT. Veja `LICENSE` para mais informações.
