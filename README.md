# Hi, I'm Rashad 👋
### Full-Stack .NET & Angular Software Engineer

[![Target Markets](https://img.shields.io/badge/Remote%20Contracts-US%20%7C%20UK%20%7C%20EU%20%7C%20AU%20%7C%20CA-4f46e5?style=for-the-badge)](#)
[![Primary Stack](https://img.shields.io/badge/Primary%20Stack-.NET%208%20%7C%20C%23%20%7C%20Angular%20%7C%20SQL%20Server-239120?style=for-the-badge)](#)
[![Automated Tests](https://img.shields.io/badge/Verified%20Tests-85%20Passing-success?style=for-the-badge)](#)
[![Email](https://img.shields.io/badge/Email-rashadhaq7%40gmail.com-D14836?style=for-the-badge&logo=gmail)](mailto:rashadhaq7@gmail.com)

---

### 👨‍💻 Professional Summary
I am a full-stack software engineer with **~3 years of commercial experience** designing, building, and maintaining business-critical web applications, enterprise APIs, and scalable backends.

- **Primary Backend:** C#, .NET 8 LTS, ASP.NET Core Web API, Entity Framework Core, SQL Server, Clean Architecture, REST API Design, Background Services (`IHostedService`).
- **Frontend Stack:** Angular (v14–v16), TypeScript, RxJS, Reactive Forms, Responsive UI Architecture.
- **Quality & Reliability:** MSTest, Moq, Integration Testing, CI/CD with GitHub Actions.
- **Focus Areas:** Enterprise SaaS platforms, billing/invoicing systems, background worker workflows, API integrations, and application performance tuning.

*Available for remote contract engagements, freelance project delivery, and technical consulting partnerships across the US, UK, Europe, Australia, and Canada.*

---

### 🌟 Flagship Portfolio Projects

#### 1. [ClientFlow — Client & Project Operations Platform](https://github.com/RASHA2702/ClientFlow)
> **Stack:** C# 12 • ASP.NET Core 8 • Angular 16 • SQL Server • Clean Architecture • MSTest & Moq  
> **Status:** [![Tests](https://img.shields.io/badge/Tests-29%20Passed-success)](https://github.com/RASHA2702/ClientFlow) [![Architecture](https://img.shields.io/badge/Architecture-Clean%20%2F%20DDD-green)](https://github.com/RASHA2702/ClientFlow/blob/master/docs/ARCHITECTURE.md)

- Comprehensive operations and contract governance platform for software agencies and consultancies.
- **Capabilities:** Multi-currency invoice denomination (USD, EUR, GBP, AUD, CAD), milestone budget tracking, 5-stage task Kanban board, task-linked billable time tracking with daily hour caps, automated invoice calculation engine with commercial `AwayFromZero` midpoint rounding, and sanitized CSV reporting (CWE-1236 defense).
- **Engineering Highlights:** Strict 4-tier Clean Architecture, RFC 9457 `ProblemDetails` error handling, distributed `X-Correlation-ID` tracing, dual-mode persistence (In-Memory + SQL Server LocalDB), and 29 automated unit/service tests.

#### 2. [IntegrationWatch — Resilient API & Webhook Monitoring Engine](https://github.com/RASHA2702/IntegrationWatch)
> **Stack:** C# 12 • .NET 8 • Resilience Patterns • Background Workers • Serilog Observability • SQL Server  
> **Status:** [![Tests](https://img.shields.io/badge/Tests-27%20Passed-success)](https://github.com/RASHA2702/IntegrationWatch) [![Security](https://img.shields.io/badge/Security-SSRF%20Guard-blue)](https://github.com/RASHA2702/IntegrationWatch/blob/master/docs/RESILIENCE.md)

- High-throughput endpoint health monitoring and synthetic probe scheduler running as a .NET `BackgroundService` with controlled concurrency (`Parallel.ForEachAsync`).
- **Capabilities:** SSRF prevention engine blocking loopback, private subnets, and cloud metadata (`169.254.169.254`), exponential backoff with jitter on transient codes, linked `CancellationToken` timeouts, NIST Nearest-Rank latency percentiles (P50/P95/P99), and automated incident generation with self-healing recovery.
- **Engineering Highlights:** Thread-safe concurrent execution, fast failure on deterministic 4xx client errors without wasteful retries, RFC 9457 problem details with internal error sanitization (CWE-209 defense), and 27 automated tests.

#### 3. [DocumentOps — Automated Invoice Ingestion & Verification Engine](https://github.com/RASHA2702/DocumentOps)
> **Stack:** C# 12 • ASP.NET Core 8 • Clean Architecture • Regex Rules • Pluggable Extractor • ERP Ingestion  
> **Status:** [![Tests](https://img.shields.io/badge/Tests-29%20Passed-success)](https://github.com/RASHA2702/DocumentOps) [![HITL](https://img.shields.io/badge/Workflow-Human--in--the--Loop-blue)](https://github.com/RASHA2702/DocumentOps/blob/master/docs/ARCHITECTURE.md)

- Enterprise accounts payable ingestion engine combining high-speed deterministic regex parsing with an extensible document intelligence pipeline.
- **Capabilities:** 9 cross-field invariant rules (including `|Subtotal + Tax - Total| <= 0.01` arithmetic auditing, ISO 4217 currency subunit precision checks, and line item duplicate detection), rule-weighted confidence scoring ($0.00 - 1.00$), Human-in-the-Loop review queue, SHA-256 deduplication, and UBL-modeled JSON / CWE-1236 sanitized CSV export.
- **Engineering Highlights:** Strict approval barriers blocking unverified financial errors, zero-hallucination deterministic parsing fallback, RFC 9457 problem details, and 29 automated unit/integration tests.

---

### 🛠️ Technical Competencies

```
Backend:           C# 12, .NET 8 LTS, ASP.NET Core Web API, Entity Framework Core, LINQ, Dapper
Frontend:          Angular (14-16), TypeScript, RxJS, HTML5, CSS3/SCSS, Reactive Forms, SaaS UI
Databases:         Microsoft SQL Server (T-SQL, Stored Procedures, Index Tuning), SQL Server LocalDB
Architecture:      Clean Architecture, Domain-Driven Design (DDD), Background Services (IHostedService), Resilience Engineering
Testing:           MSTest, Moq, Integration Testing, TDD (85 Passing Tests Across Portfolio — 100% Pass Rate)
Security:          CWE-1236 Neutralization, SSRF Prevention, RFC 9457 Problem Details, CWE-209 Info-Leak Defense
DevOps & Tooling:  Docker, Docker Compose, GitHub Actions CI/CD, Git, Postman, Linux/Windows
```

---

### 🤝 Engagement Models for International Clients

1. **Fixed-Price Project Delivery:** Full-cycle scoping, architecture, implementation, automated testing, and deployment for SaaS MVPs, internal tooling, and client portals.
2. **Dedicated Retainer / Contract Engineering:** Remote contract engineer embedded directly into your agile sprint cadence (US, UK, European, or Australian timezone overlap).
3. **API Modernization & Maintenance:** Upgrading legacy .NET / .NET Framework systems to modern .NET 8, implementing resilience policies, containerization, and establishing automated test coverage.

---

### 📬 Contact & Availability

- **Direct Email:** [rashadhaq7@gmail.com](mailto:rashadhaq7@gmail.com)
- **GitHub:** [@RASHA2702](https://github.com/RASHA2702)
- **Location:** India (Available for remote contracts with dedicated timezone overlap).
