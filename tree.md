Sysotto.Identity/
├── src/
│   ├── Sysotto.Identity.Core/
│   │   ├── CORE_README.md          ◄─ Documentação da camada Core
│   │   ├── Entities/    (User, Role, Tenant, Company, AuditLog)
│   │   ├── Enums/       (UserType, SubscriptionStatus, etc)
│   │   ├── Interfaces/  (IUserRepository, IAuthService, etc)
│   │   └── ValueObjects/ (Email, PasswordHash, PhoneNumber, Address)
│   │
│   ├── Sysotto.Identity.Infrastructure/
│   │   ├── INFRA_README.md        ◄─ Documentação da camada Infrastructure
│   │   ├── Data/        (IdentityDbContext, Migrations)
│   │   ├── Repositories/ (UserRepository, CompanyRepository, etc)
│   │   └── Services/    (AuthService, MfaService, RateLimitingService, etc)
│   │
│   ├── Sysotto.Identity.Api/
│   │   ├── API_README.md           ◄─ Documentação da camada Api
│   │   ├── Controllers/ (AuthController, MfaController, UsersController, etc)
│   │   ├── Dtos/        (LoginRequest, RegisterRequest, UserResponse, etc)
│   │   ├── Filters/     (ExceptionFilter, AuthorizationFilter)
│   │   └── Middleware/  (JwtValidation, TenantResolution, RateLimiting)
│   │
│   └── Sysotto.Identity.Client/
│       ├── CLIENT_README.md       ◄─ Documentação do SDK Client
│       ├── IdentityApiClient.cs
│       └── Dtos/
│
├── tests/
│   ├── Sysotto.Identity.UnitTests/
│   ├── Sysotto.Identity.IntegrationTests/ (com Testcontainers)
│   └── ...
│
├── docs/
│   └── ai/          (Arquitetura técnica detalhada)
│
├── .github/
│   └── workflows/
│       ├── ci-cd.yml       (Build + Testes)
│       └── publish.yml     (Publicar pacotes NuGet via tags)
│
├── nupkg/           (Armazena pacotes .nupkg e .snupkg)
├── setup-local-nuget.sh  (Script para feed NuGet local)
└── Sysotto.Identity.slnx