# 🎯 Sysotto.Identity - Showcase

> **Módulo moderno de gestão de identidade e autenticação para .NET 10**  
> 
> Sistema completo de Identity Management distribuído como pacote NuGet, com suporte a multi-tenancy, OAuth2/OIDC e arquitetura limpa.

## 🚀 Destaques Técnicos

- **.NET 10** com C# 14
- **Clean Architecture** + CQRS
- **PostgreSQL 17** + Entity Framework Core
- **Multi-tenancy** com Row-Level Security
- **OAuth2/OIDC** via OpenIddict
- **Docker** + GitHub Actions CI/CD

## 📸 Screenshots

### 1. Autenticação e Login
![Login Flow](capEx01.png)

### 2. Gestão de Usuários
![User Management](capEx02.png)

### 3. Controle de Acesso (RBAC)
![Role-Based Access](capEx03.png)

### 4. API Documentation (Swagger)
![API Docs](capEx04.png)

### 5. Multi-Tenancy Dashboard
![Tenancy](capEx05.png)

## 🏗️ Arquitetura

```
┌─────────────────────────────────────────┐
│          Sysotto.Identity.Api           │
│     (Controllers, Middleware, DTOs)     │
├─────────────────────���───────────────────┤
│     Sysotto.Identity.Infrastructure     │
│   (EF Core, Repositories, Services)     │
├─────────────────────────────────────────┤
│        Sysotto.Identity.Core            │
│    (Entities, VOs, Interfaces, Rules)   │
└─────────────────────────────────────────┘
```

## 🔑 Funcionalidades Principais

✅ Autenticação JWT + Refresh Token  
✅ Usuários Internos (Colaboradores) e Externos (Clientes)  
✅ Diferenciação PF/PJ  
✅ Sistema de Planos Variáveis  
✅ Multi-tenancy com Isolamento  
✅ OAuth2/OIDC Server  
✅ Rate Limiting + Security Headers  
✅ Observabilidade (Serilog, Health Checks)  

## 📦 Distribuição como NuGet

```bash
dotnet add package Sysotto.Identity.Core
dotnet add package Sysotto.Identity.Infrastructure
dotnet add package Sysotto.Identity.Api
```

## 🔗 Links

- 📦 [Repositório Principal](https://github.com/OttoF77/Sysotto.Identity)
- 📚 [Documentação Completa](https://github.com/OttoF77/Sysotto.Identity/tree/main/docs)

## 👨‍💻 Sobre o Desenvolvedor

**Otto Freitag**  
Desenvolvedor .NET especializado em arquitetura de software e sistemas distribuídos.

[![GitHub](https://img.shields.io/badge/GitHub-OttoF77-181717?logo=github)](https://github.com/OttoF77)

---

**Projeto Privado** - Todos os direitos reservados.