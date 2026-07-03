# ⚠️ Mongock is Deprecated
**Status:**: Mongock is no longer actively maintained as of **2026-07-01**.
No new features will be added. Critical security fixes may be considered on a best-effort basis only.

Existing Mongock versions will continue to work as they do today, but we recommend using **[Flamingock](https://github.com/flamingock/flamingock-java)** for new projects and future development.

---

## Meet Flamingock 🚀
We are the original authors of Mongock. Over the past couple of years, we have been building **[Flamingock](https://github.com/flamingock/flamingock-java)**: a new platform inspired by what worked well in Mongock, but designed for a broader scope.

Mongock helped teams evolve NoSQL databases safely. Flamingock takes that idea further: auditable, deterministic evolution across your entire system.

Flamingock supports the core MongoDB and NoSQL migration use cases Mongock was known for, while also extending change orchestration beyond databases to areas such as message queues, events, contracts, APIs, configs, feature flags, and more.

It also introduces stronger foundations for operational safety, including improved failure handling, recovery, retries, rollback support, and execution visibility.

A Flamingock Cloud offering is also in progress, focused on giving teams a central control plane to monitor executions, inspect audit history, manage environments, understand failures, and govern changes across services and systems.

---

## Why the change?
Real-world systems rarely evolve in one place only.

Database migrations are still important, but modern applications also require coordinated changes across services, infrastructure, events, APIs, configuration, and operational rules.

**Flamingock was built to support that broader model from day one.**

It is not a drop-in continuation of Mongock. It is a new platform, built by the same team, carrying forward Mongock’s core migration ideas while expanding them into system-wide change orchestration with stronger auditability, safer recovery, and better operational control.

---

## Flamingock highlights
- Robust support for MongoDB and NoSQL migrations, covering everything previously offered by Mongock
- Designed **from the ground up with auditability, determinism, and governance at its core**
- Auditable and deterministic change execution
- Improved failure handling and recovery
- Retry, rollback, and operational safety mechanisms
- Multi-stage workflows
- Flexible/low‑code templates for defining changes
- Native GraalVM support
- Cloud control plane for monitoring, audit history, environments, failures, and team governance


Learn more in the docs → [Overview](https://docs.flamingock.io/get-started/Introduction)

> Same creators. Broader scope. Better foundations.

👉[start here](https://github.com/flamingock/flamingock-java)
---

## What about existing Mongock users?

- Your current versions will keep working as-is.
- We strongly recommend evaluating Flamingock for new projects or when planning significant changes.
- Flamingock introduces a different architecture, but we’ve made it easy to transition when you're ready.
- Upgrade help: see **[How to move from Mongock to Flamingock](https://docs.flamingock.io/resources/coming-from-mongock)**
