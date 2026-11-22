# Olá, eu sou o Blayner 👋

Desenvolvedor **back-end** com foco em **.NET** e **Node.js/TypeScript**. Gosto de sistemas distribuídos, performance e de decisões de arquitetura bem documentadas: cada projeto abaixo traz ADRs explicando o *porquê*, testes em camadas e CI rodando contra infraestrutura real.

## 🧭 Portfólio

| Projeto | O que é | Destaques | Stack |
|---|---|---|---|
| [**PaymentLedger**](https://github.com/blayner/PaymentLedger) | Plataforma de pagamentos com livro-razão | Event Sourcing, CQRS com projeções, partidas dobradas garantidas no domínio, transactional outbox, idempotência com fingerprint do payload, OpenTelemetry | .NET 10 · PostgreSQL |
| [**EventIngestor**](https://github.com/blayner/EventIngestor) | Serviço de ingestão de eventos de alto throughput | gRPC + REST, `System.IO.Pipelines`, `Channel<T>` com backpressure, pooling, BenchmarkDotNet e k6 | .NET 10 · Prometheus · Grafana |
| [**FeatureFlare**](https://github.com/blayner/FeatureFlare) | Feature flags e experimentos A/B | Avaliação local nos SDKs, streaming via SSE, bucketing com MurmurHash3 idêntico em .NET e TS | .NET 10 · TypeScript · PostgreSQL |
| [**NexusCommerce**](https://github.com/blayner/NexusCommerce) | E-commerce em monólito modular | DDD + arquitetura hexagonal, máquina de estados de pedido, saga de checkout, BullMQ, cache Redis, métricas Prometheus | NestJS 12 · Prisma · PostgreSQL · Redis |
| [**CollabSync**](https://github.com/blayner/CollabSync) | Backend de colaboração em tempo real | CRDTs com Yjs, presença, escala horizontal via Redis pub/sub sem sticky sessions, log de updates + snapshots | Node.js · WebSocket · PostgreSQL · Redis |
| [**ts-outcome**](https://github.com/blayner/ts-outcome) | Biblioteca open source de `Result`/`Option` | Tipagem avançada, erros acumulados no tipo, do-notation com generators, 100% de cobertura, < 2 kB gzip | TypeScript |

## 🛠️ Stack

**Linguagens & runtimes:** C# · .NET 10 · TypeScript · Node.js
**Frameworks:** ASP.NET Core · EF Core · gRPC · NestJS · Fastify
**Dados & mensageria:** PostgreSQL · Redis · BullMQ · Event Sourcing
**Qualidade:** xUnit · Testcontainers · Vitest · Jest · BenchmarkDotNet · k6
**Infra & observabilidade:** Docker · GitHub Actions · OpenTelemetry · Prometheus · Grafana

## 📐 Como eu trabalho

- **Decisões documentadas**: ADRs com contexto, alternativas e trade-offs.
- **Testes em camadas**: unidade → integração com banco real → e2e, tudo no CI.
- **Operável desde o início**: health checks, logs estruturados, métricas e traces.
- **Sem dependência desnecessária**: prefiro entender o problema a adicionar uma lib.
