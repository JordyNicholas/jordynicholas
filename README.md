<h1 align="center">Jordy Nicholas</h1>

<p align="center">
  <strong>Engenheiro de Software Pleno</strong><br />
  Mid-level Software Engineer
</p>

<p align="center">
  TypeScript · Node.js · Java · AWS Serverless<br />
  Coforge · Cruzeiro, SP
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jordy-nicholas"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:jordyncdasilva@live.com"><strong>jordyncdasilva@live.com</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/JordyNicholas/TokenForge"><strong>TokenForge</strong></a>
</p>

<p align="center">
  <a href="#portugues">Português</a>
  &nbsp;·&nbsp;
  <a href="#english">English</a>
</p>

<p align="center">
  PostgreSQL 15.12 → 17.7 on RDS Aurora, zero downtime
  &nbsp;·&nbsp;
  10,000+ Step Functions executions
</p>

---

<a id="portugues"></a>

## Português

Engenheiro de Software Pleno com cerca de 2 anos e meio em sistemas distribuídos. Na Coforge, na continuidade do trabalho iniciado na Encora, atuo com TypeScript (Node.js), Java e AWS Serverless (Lambda, API Gateway, Step Functions e SQS).

O que mais pesa em produção:

- Orquestrei a terminação de mais de 10.000 execuções travadas do Step Functions com uma arquitetura recursiva em Lambda, depois de um gargalo de concorrência na conta AWS.
- Planejei e executei o upgrade de PostgreSQL 15.12 para 17.7 no RDS Aurora sem downtime, com deploy Blue/Green.
- Na Coforge, entrego pipeline de exportação de dados sensíveis, Lambda Authorizer para integrações com terceiros e o ciclo de vida de artefatos de CI/CD no JFrog Artifactory.

### Projetos

Clique no nome para abrir o código.

**[TokenForge](https://github.com/JordyNicholas/TokenForge)** — projeto pessoal, em atividade. Reduz custo de tokens em fluxos de agentes de código: um CLI em TypeScript estima o risco do contexto, uma extensão do VS Code trata os arquivos abertos e um dashboard em React mostra o antes e o depois. Há adaptadores para Copilot, Cursor e Claude, testes e um workflow mensal no GitHub Actions.

<details>
<summary>O que o TokenForge faz, em três passos</summary>

1. **Token Risk.** Varre o repositório e marca contexto caro e de pouco valor.
2. **Policy Pack.** Gera instruções e exclusões no formato de cada ferramenta (Copilot, Cursor, Claude).
3. **Savings Proof.** Publica um relatório de tokens antes/depois para o dashboard.

O modo padrão é heurístico, sem chamar um modelo. O enriquecimento com LLM é opcional.

</details>

**[ts-monolith](https://github.com/JordyNicholas/ts-monolith)** e **[nextjs-boilerplate](https://github.com/JordyNicholas/nextjs-boilerplate)** — base de referência pessoal, não um produto em produção. API em monólito modular (Fastify, Prisma, PostgreSQL, autenticação multi-tenant, fila e contrato OpenAPI) e um console Next.js que consome os tipos gerados desse contrato, com opção de sessão em cookie httpOnly.

### Formação

- Pós-graduação Lato Sensu em Engenharia de Software — PUC Minas (2024–2025)
- Bacharelado em Engenharia da Computação — UNISAL, Lorena (2019–2023)
- General Standard Course, Inglês C1 — Bayswater College, Liverpool (2023)

### Stack

| | |
| --- | --- |
| Linguagens | TypeScript, JavaScript, Java, Python |
| Backend | Node.js, Spring Boot, Fastify, Prisma |
| Frontend | React, Next.js |
| Cloud | AWS Lambda, API Gateway, Step Functions, SQS, RDS Aurora, S3, CloudFormation, CDK |
| Dados | PostgreSQL, DynamoDB, MySQL |
| Testes | Jest, Vitest |

<details>
<summary>Certificações</summary>

- AWS Certified Cloud Practitioner (2024)
- Trilha de IA generativa — Coursera, com Google e Amazon (2025): fundamentos, LangChain e agentes
- Santander Coders — Java + Angular e backend web (2023)

</details>

Português nativo · Inglês fluente (C1)

Fora do código, converso sobre esporte, jogos, música e viagem. [Instagram](https://instagram.com/jordynicholas)

[English](#english)

---

<a id="english"></a>

## English

Mid-level Software Engineer with about two and a half years on distributed systems. At Coforge, continuing the work started at Encora, I build with TypeScript (Node.js), Java, and AWS Serverless (Lambda, API Gateway, Step Functions, and SQS).

Production work I point to:

- Orchestrated the termination of 10,000+ stuck Step Functions executions with a recursive Lambda architecture, after an account-level concurrency bottleneck.
- Planned and ran a PostgreSQL upgrade from 15.12 to 17.7 on RDS Aurora with no downtime, using Blue/Green deployments.
- At Coforge I deliver a sensitive-data export pipeline, a Lambda Authorizer for third-party integrations, and CI/CD artifact lifecycle management in JFrog Artifactory.

### Projects

The name opens the repository.

**[TokenForge](https://github.com/JordyNicholas/TokenForge)** — personal project, actively developed. It cuts token cost in coding-agent workflows: a TypeScript CLI scores context risk, a VS Code extension handles open files, and a React dashboard shows before and after. Adapters cover Copilot, Cursor, and Claude, with tests and a monthly GitHub Actions workflow.

<details>
<summary>What TokenForge does, in three steps</summary>

1. **Token Risk.** Scans a repository and flags expensive, low-value context.
2. **Policy Pack.** Writes instructions and exclusions in each tool’s format (Copilot, Cursor, Claude).
3. **Savings Proof.** Publishes a before/after token report for the dashboard.

The default mode is heuristic and does not call a model. LLM enrichment is optional.

</details>

**[ts-monolith](https://github.com/JordyNicholas/ts-monolith)** and **[nextjs-boilerplate](https://github.com/JordyNicholas/nextjs-boilerplate)** — a personal reference stack, not a production product. A modular-monolith API (Fastify, Prisma, PostgreSQL, multi-tenant auth, a queue, and an OpenAPI contract) plus a Next.js console that consumes the generated types, with an optional httpOnly-cookie session.

### Education

- Lato Sensu postgraduate degree, Software Engineering — PUC Minas (2024–2025)
- Bachelor’s degree, Computer Engineering — UNISAL, Lorena (2019–2023)
- General Standard Course, C1 English — Bayswater College, Liverpool (2023)

### Stack

| | |
| --- | --- |
| Languages | TypeScript, JavaScript, Java, Python |
| Backend | Node.js, Spring Boot, Fastify, Prisma |
| Frontend | React, Next.js |
| Cloud | AWS Lambda, API Gateway, Step Functions, SQS, RDS Aurora, S3, CloudFormation, CDK |
| Data | PostgreSQL, DynamoDB, MySQL |
| Testing | Jest, Vitest |

<details>
<summary>Certifications</summary>

- AWS Certified Cloud Practitioner (2024)
- Generative AI path — Coursera, with Google and Amazon (2025): foundations, LangChain, and agents
- Santander Coders — Java + Angular and web backend (2023)

</details>

Portuguese: native · English: fluent (C1)

Outside of code I talk about sports, games, music, and travel. [Instagram](https://instagram.com/jordynicholas)

[Português](#portugues)
