# Icaro William

**Senior Python Engineer | Python Specialist: FastAPI · Django · Flask | PostgreSQL · Redis · AWS · Docker · Kubernetes**

Python specialist with 7 years of Python (since 2019, building and teaching courses and my own products, and since 2024 professionally in fintech and AgTech) on top of 17+ years in backend development. Open to new opportunities (remote).

[LinkedIn](https://www.linkedin.com/in/tio-jobs) · [YouTube](https://www.youtube.com/@tiojobs) · icarojobsoficial@gmail.com

[English](#english) | [Português](#português)

---

## English

### Selected results

- **Fintech (MaisTODOS):** rebuilt the banking core from framework-less AWS Lambda to async FastAPI, scaling it from 500 to 3 million requests per minute (6,000x); event-driven payments with SQS and Lambda.
- **AgTech (Drakkar):** shipped an AWS Bedrock AI assistant in ~3 weeks, serving ~800 farmers at ~US$ 340/month with 87% user satisfaction; cut PostGIS queries on tables with millions of rows from ~2 s to ~2 ms.
- **EdTech (PreparaTODOS, now Refuturiza):** PagSeguro subscription integration converted 70% of a 10k-student base into subscribers (~7k subscribers, ~R$ 139k MRR).
- **Marketplaces (Universidade Marketplaces):** as Software Architect leading a team of 6, delivered 6 projects that cut monthly costs by 10% and increased revenue by 20%.

### Featured project

**[agro-rag-api](https://github.com/icarojobs/agro-rag-api)**: FastAPI, PostgreSQL/pgvector, Redis, LangGraph, AWS (SNS, SQS, DynamoDB on floci), Kubernetes.

- RAG API with a LangGraph agent; MRR from 0.752 to 0.981 on 72 labeled questions.
- Redis cache-aside: p95 from 360 ms to 4 ms and 114 to 162 req/s at 50 users; Redis down under load: 0 failures.
- Retries with backoff and jitter, circuit breakers, `/livez` and `/readyz` probes.
- Async ingestion: SNS fan-out, SQS with DLQ redrive, idempotent worker, DynamoDB.
- Kubernetes (kustomize on kind) with HPA: 2 to 6 replicas under load, 0 failures.
- 126 tests at 97% coverage; docker compose and GitHub Actions CI.

### Other projects

| Project | Stack | Highlights |
|---|---|---|
| [orderflow-rs](https://github.com/icarojobs/orderflow-rs) | Rust, Tokio, gRPC, Kafka | Order matching engine; ~107k orders/s end to end with p99 of 1.4 ms |
| [laravel-orders-platform](https://github.com/icarojobs/laravel-orders-platform) | Laravel, React, RabbitMQ, Pest | N+1 fix took p95 from 1,212 ms to 61 ms; 97.7% coverage |

Every project runs with `docker compose up` and ships with CI, tests and measured results in its README.

### Tech stack

- **Python:** FastAPI, Django, Django REST Framework, Flask, Pydantic, SQLAlchemy, Alembic, asyncio, pytest
- **Data & messaging:** PostgreSQL, Redis, PostGIS, DynamoDB, AWS SQS/SNS, RabbitMQ, Kafka
- **Cloud & DevOps:** AWS (Lambda, S3, RDS, EC2, Bedrock), Docker, Kubernetes, GitHub Actions, GitLab CI, OpenTelemetry, Prometheus, Grafana
- **AI:** LLMs, RAG, LangChain, LangGraph, Ollama, Hugging Face, MLflow, AI-assisted and agentic coding tools
- **Also:** PHP/Laravel, Rust, TypeScript, Go, SQL

### Languages

Portuguese (native) · English (B2)

---

## Português

**Engenheiro Python Sênior | Especialista em Python: FastAPI · Django · Flask | PostgreSQL · Redis · AWS · Docker · Kubernetes**

Especialista em Python com 7 anos de Python (desde 2019, criando e ensinando cursos e produtos próprios e, desde 2024, profissionalmente em fintech e AgTech), sobre mais de 17 anos de backend. Aberto a novas oportunidades (remoto).

### Resultados

- **Fintech (MaisTODOS):** reestruturei o core bancário de AWS Lambda sem framework para FastAPI assíncrono, de 500 para 3 milhões de requisições por minuto (6.000x); pagamentos orientados a eventos com SQS e Lambda.
- **AgTech (Drakkar):** assistente de IA com AWS Bedrock em produção em ~3 semanas, atendendo ~800 produtores a ~US$ 340/mês com 87% de satisfação; consultas PostGIS em tabelas com milhões de linhas de ~2 s para ~2 ms.
- **EdTech (PreparaTODOS, atual Refuturiza):** assinaturas via PagSeguro converteram 70% de uma base de 10 mil alunos (~7 mil assinantes, ~R$ 139 mil de receita recorrente mensal).
- **Marketplaces (Universidade Marketplaces):** como Arquiteto de Software, liderando um time de 6 pessoas, entreguei 6 projetos que reduziram os custos mensais em 10% e aumentaram a receita em 20%.

### Projeto em destaque

**[agro-rag-api](https://github.com/icarojobs/agro-rag-api)**: FastAPI, PostgreSQL/pgvector, Redis, LangGraph, AWS (SNS, SQS, DynamoDB em floci), Kubernetes.

- API de RAG com agente LangGraph; MRR de 0,752 para 0,981 em 72 perguntas rotuladas.
- Cache Redis: p95 de 360 ms para 4 ms e de 114 para 162 req/s com 50 usuários; Redis fora do ar sob carga: 0 falhas.
- Retry com backoff e jitter, circuit breaker e probes `/livez` e `/readyz`.
- Ingestão assíncrona: SNS, SQS com redrive para DLQ, worker idempotente, DynamoDB.
- Kubernetes (kustomize no kind) com HPA: de 2 a 6 réplicas sob carga, 0 falhas.
- 126 testes com 97% de cobertura; docker compose e CI no GitHub Actions.

### Outros projetos

- **[orderflow-rs](https://github.com/icarojobs/orderflow-rs):** motor de matching de ordens em Rust; ~107 mil ordens/s ponta a ponta com p99 de 1,4 ms.
- **[laravel-orders-platform](https://github.com/icarojobs/laravel-orders-platform):** plataforma de pedidos em Laravel; correção de N+1 levou o p95 de 1.212 ms para 61 ms.

Todos rodam com `docker compose up` e trazem CI, testes e resultados medidos no README.

### Idiomas

Português (nativo) · Inglês (B2)
