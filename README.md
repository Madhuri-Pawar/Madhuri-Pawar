# Hi, I'm Madhuri Pawar 👋

**Full-Stack Engineer · FinTech & Payments** · Pune, India

I build reliable payment systems and the tooling around them: payment APIs, ISO 20022 Request-to-Pay flows, production-issue investigation, and AI agents that help engineers diagnose and review payment code faster.

**Stack:** TypeScript · NestJS · Node.js · React · PostgreSQL · AWS · WebSockets · Claude Code · MCP · ISO 20022

---

## Featured projects

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

## What I focus on

- **Payment correctness:** idempotency, safe retries, reconciliation, and never charging twice.
- **Evidence-driven debugging:** root causes backed by code, logs, and data, not guesses.
- **AI-assisted engineering:** turning repeatable investigation and review work into reusable agent workflows.

---

📫 Reach me through [GitHub](https://github.com/Madhuri-Pawar)
