# myflix-api

> 🇧🇷 Backend da plataforma de streaming MyFlix, desenvolvido com ASP.NET Core e SQL Server, seguindo arquitetura em camadas (Domain, Application, Infrastructure, API).

> 🇺🇸 Backend of the MyFlix streaming platform, developed with ASP.NET Core and SQL Server, following a layered architecture (Domain, Application, Infrastructure, API).

---

## 📁 Estrutura / Structure

- `MyFlix.API/`: Camada de apresentação (Controllers, Swagger) | Presentation layer (Controllers, Swagger)
- `MyFlix.Application/`: Casos de uso, DTOs, interfaces | Use cases, DTOs, interfaces
- `MyFlix.Domain/`: Entidades de domínio, regras de negócio | Domain entities, business rules
- `MyFlix.Infrastructure/`: Acesso a dados, serviços externos, JWT | Data access, external services, JWT, handling

## 🚀 Início Rápido / Quick Start

### 🇧🇷 Requisitos / 🇺🇸 Requirements

- .NET 8 SDK
- SQL Server (local ou remoto)

### 🧪 Executar localmente / Run locally

```bash
dotnet restore
dotnet build
dotnet run --project MyFlix.API

