# Hi, I'm Jovan

I'm a software engineer in Belgrade. I've been building .NET and Angular software at RareCrew since March 2022, mostly on a live accounting system, where correctness, careful changes, and not breaking anyone's financial data matter a lot.

Outside work I build things to understand them properly. Each repo below is me taking one idea (event sourcing, multi-tenancy, messaging, real-time, CI) and working through it end to end, including the tradeoffs and the parts I haven't finished yet.

## What I work with
- **Backend:** C#, .NET, ASP.NET Core, EF Core, Minimal APIs
- **Frontend:** Angular, TypeScript, RxJS
- **Data:** SQL Server, PostgreSQL, Redis, SQLite
- **Architecture:** modular monoliths, CQRS, DDD, event sourcing, microservices and their tradeoffs
- **Delivery:** Docker, Testcontainers, GitHub Actions, integration testing
- **AI:** I spend a lot of time with agentic tools (Claude, Codex, Cursor), setting up harnesses and orchestrating agents, and I review and verify what they produce

## Projects
| Project | What it explores |
| --- | --- |
| [MultiTenantRecipeBook](https://github.com/ckejoM/MultiTenantRecipeBook) | Multi-tenant SaaS: EF Core global query filters, JWT tenant context, roles, vertical slices |
| [EcommerceCore](https://github.com/ckejoM/EcommerceCore) | Modular monolith: separate schemas per module, CQRS with MediatR, event-based module communication |
| [EventSourcedLedger](https://github.com/ckejoM/EventSourcedLedger) | Event sourcing with Marten and PostgreSQL, Wolverine commands, inline projections |
| [MicroservicesDeliveryMesh](https://github.com/ckejoM/MicroservicesDeliveryMesh) | Services behind a YARP gateway, RabbitMQ messaging with Wolverine, a saga across services |
| [Portfolio-CICD](https://github.com/ckejoM/Portfolio-CICD) | Containerized full stack, Testcontainers integration tests, GitHub Actions |
| [CollaborativeWhiteboard](https://github.com/ckejoM/CollaborativeWhiteboard) | Real-time SignalR with a Redis backplane, RxJS throttling, Canvas |
| [TechNewsAggregator](https://github.com/ckejoM/TechNewsAggregator) | Background workers, caching, and resilience pipelines around external APIs |
| [PersonalAssetVault](https://github.com/ckejoM/PersonalAssetVault) | Clean Architecture, JWT auth, Angular Signals |
| [ObservabilityHub](https://github.com/ckejoM/EnterpriseObservabilityHub) | OpenTelemetry, Prometheus, Grafana, and ELK on two small services |

## What I care about
I like architecture when it makes future changes safer, not when it only makes the diagrams look better. The question I keep coming back to:

> Can this system be changed, tested, and understood without guessing?

[LinkedIn](https://www.linkedin.com/in/jovan-madzic-12093b202/)
