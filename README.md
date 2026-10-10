# Hi, I'm Madhuri Pawar 👋

**Full-Stack Software Engineer · FinTech & Payments** · Pune, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-madhuri--d--pawar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhuri-d-pawar)
[![Email](https://img.shields.io/badge/Email-pawarmadhuri667%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:pawarmadhuri667@gmail.com)

I'm a full-stack engineer with 4 years of experience building scalable, secure fintech and healthcare (EHR) applications with React, Angular, NestJS, PostgreSQL, and AWS. I currently work at **BTB (Be The Bank)**, an Israeli fintech, where I build payment and verification systems on **MASAV's ISO 20022 rail**, own system design for new features, and build AI-assisted engineering workflows with custom Claude skills, plugins, and agents.

---

## 🚀 What I've built

- **Bank-account ownership verification:** a standalone microservice that uses ISO 20022 messaging over MASAV to confirm account ownership directly with banks in ~5–10 seconds, replacing manual document uploads. It delivers results through SQS webhook push with a polling fallback.
- **Request-to-Pay instant payments:** a business sends a payment request, the customer approves it in their own bank, and an instant credit settles it. Idempotent requests, webhook push plus status pull, retries, and a circuit breaker ensure every request ends as paid, failed, cancelled, or expired.
- **Security hardening:** RSA-PSS/SHA-256 signing, Digest Authentication, XXE- and ReDoS-safe XML parsing, AWS Secrets Manager key management, idempotency constraints, and race-free concurrent processing.
- **Payment automation:** an end-to-end broker commission payout system (bank transfers and wallet payouts) with fix-and-retry for failures, which turned a month-long manual process into a one-click approval.
- **Payment gateway integration:** led the Pelecard integration with idempotent flows, retry strategies, a reconciliation engine, a transaction orchestrator, and a partner sandbox.
- **Compliance engine:** a matrix-driven engine that gates deposits, withdrawals, and transfers for a 50K+ user platform, combined with AU10TIX identity verification.
- **Platform modernization:** led the migration of a legacy .NET/KnockoutJS platform to React and NestJS.

---

## 📂 Featured projects

### 🤖 [fintech-agent-skills](https://github.com/Madhuri-Pawar/fintech-agent-skills)
Claude Code plugins and AI agent skills for fintech engineering.
- **Jira AI Assistant Plugin:** investigates Jira production issues by correlating ticket context, repository code, commit history, and runtime evidence to identify the root cause and recommend a fix.
- **AI-Powered Payment Code Review:** reviews payment code for correctness, defects, edge cases, and payment-flow risks (duplicate charges, idempotency, provider timeouts, webhook replay).
- **Payment Request Assistant:** answers questions about ISO 20022 Request-to-Pay payments (status, failures, cancellations, message journeys) using read-only SQL.

`Claude Code` `Agent Skills` `MCP` `Jira` `PostgreSQL` `ISO 20022`

### 💳 [Payment Orchestrator: system design case study](https://github.com/Madhuri-Pawar/Payment-Orchestrator-)
How to design a payment platform that routes across multiple payment service providers (PSPs) without making a merchant's revenue depend on a single provider. It covers the business problem through HLD/LLD, the payment state machine, API design, idempotency, timeouts with unknown outcomes, duplicate and out-of-order webhooks, reliability, security, observability, and a decision log of trade-offs.

`System Design` `Payments` `Multi-PSP` `Reliability` `State Machines`

### 📈 [Live Stock Dashboard](https://github.com/Madhuri-Pawar/live-stock) · [Live demo](https://live-stock-1-rlnp.onrender.com/)
Real-time stock price dashboard that streams ~100 ticks/sec over WebSocket and renders smoothly at 60fps. It uses per-ticker server throttling, `requestAnimationFrame` batching, virtualized rendering (about 15 DOM rows), and reconnection with exponential backoff and jitter.

`React` `Zustand` `Node.js` `WebSocket` `Performance`

---

## 🛠️ Tech stack

| Area | Technologies |
| --- | --- |
| **Languages** | TypeScript, JavaScript (ES6+), HTML5, CSS3 |
| **Frontend** | React, React Query, Redux, Angular, NgRx, RxJS, Angular Material, Tailwind CSS |
| **Backend** | NestJS, Node.js, TypeORM, REST APIs, Microservices, SQS/SNS event streaming, OAuth 2.0 / JWT |
| **Payments & Security** | ISO 20022 (pain / pacs / camt), MASAV, Request-to-Pay, mTLS, RSA-PSS signing, Idempotency, Transactional Outbox |
| **Data** | PostgreSQL, MongoDB, Caching |
| **Cloud & DevOps** | AWS (Cognito, EC2, ECR, S3, Lambda, SNS, SQS, DMS, CloudWatch), Kubernetes, Docker, Argo Workflows, Nx, GitLab CI/CD, SonarQube |
| **Testing & Observability** | Jest, unit & integration testing, SigNoz, CloudWatch |
| **AI Workflows** | Claude API, Custom Claude Skills & Plugins, MCP Servers, AI Agents, Cursor Subagents |

---

## 💼 Experience

- **Associate Software Engineer, BTB (Be The Bank)**, FinTech, Israel · Aug 2025 to present
- **Software Engineer, Thinkitive Technologies**, Pune · May 2022 to Jul 2025: grew from frontend developer to full-stack engineer, building multi-tenant healthcare (EHR) portals and real-estate products with Angular, React, Node.js, and MongoDB.

---

## 🎯 What I focus on

- **Payment correctness:** idempotency, safe retries, reconciliation, and never charging twice.
- **Evidence-driven debugging:** root causes backed by code, logs, and data, not guesses.
- **AI-assisted engineering:** turning repeatable investigation and review work into reusable agent workflows.

---

📫 **Let's connect:** [LinkedIn](https://www.linkedin.com/in/madhuri-d-pawar) · [pawarmadhuri667@gmail.com](mailto:pawarmadhuri667@gmail.com)
